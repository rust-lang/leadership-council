# Keeping membership aligned with reality

This policy outlines how the Rust Project will maintain the membership in rust-lang/team to be kept up to date.

## Goals

Why do we care about keeping membership up to date?

* Improved planning (e.g., budgeting for usage of grants and space at events)
* Elections and other processes seeking consensus don't stumble on 'maybe present' people
  * i.e., we avoid ad-hoc determinations of where to set the bar by having a consistent bar
* Providing a clear, easy off-ramp for people who want to step back
  * Avoiding the *default* being to continue indefinitely

## Identification

Once a year, the Council will ensure communication is sent out to every person in rust-lang/team (excluding those who are only alumni). This communication will, in addition to any other questions, inform respondents what teams they are *currently listed* as a part of. The survey will invite a response of "Please remove me from $TEAMS teams regardless of any other responses."

This mechanism should help identify those who are still relatively active members, but may not have realized they are a part of some team. The Council will delegate responsibility to the closest existing team to find a replacement or wind down a team if the team's lead would like to step down.

Historically, we have found that *zero* response is not uncommon despite repeated prodding. In that case, we may move a team member to alumni status on their behalf if they have been inactive in Project spaces in the last 6 months. Specifically, today, this means a check against GitHub commits, PRs, or issue comments in rust-lang org, a search on Zulip, and a search of attendee lists in public meeting minutes. Any other active team member may also vouch for someone else (e.g., to allow for those who may primarily collaborate in other venues or attend meetings but not otherwise participate). At minimum, the closest active team lead will be asked if they have seen activity recently, to provide an opportunity for this vouching.

## Retiring

During/after the above process, a PR will be filed against rust-lang/team which pings (via GitHub) all moved people and sets their status to alumni. This PR will be kept open for at least 10 days (emulating an FCP, though no FCP will be required) prior to merging.

Anyone speaking up at this point as still active will be removed from the list of removals in the PR with no questions asked.

## Rejoining

At any time, a member moved to alumni may ask to rejoin their team. In general, such requests should be near-automatically granted, though this is subject to individual team processes on joining.
