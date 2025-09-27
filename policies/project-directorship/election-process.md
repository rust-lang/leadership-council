# Project Director Election Process

## Goals

The purpose of this policy is to outline a clear and efficient process for electing new Project Directors to represent the Rust project on the board of the Rust Foundation. The process aims to achieve the following goals:

* Select candidates who fulfill the outlined candidate criteria in the [role description document](../../roles/rust-foundation-project-director.md), focusing on new leadership and diverse perspectives rather than solely prioritizing the best candidate.
    * Strive for tolerance and inclusivity by prioritizing selecting candidates that everyone can accept over selecting the first choice for only a subset of people.
* Conduct the selection process in a time-efficient manner.
* Incorporate input from a wide range of stakeholders across the entire Rust project.
* Ensure a diverse pool of qualified candidates for selection.
* Create a psychologically safe environment that values minority perspectives and encourages positive feedback, encouragement, and tolerance rather than personal preference or criticism.
* Ensure participants feel positive about their interactions and the execution of the process.
* Ensure the process is compliant with Rust Foundation bylaws and Delaware corporation law.

## Description

### Setup

* The council selects a facilitator by consent:
    * Any team member can suggest a facilitator or volunteer themselves.
    * The facilitator must not be a nominee in the election and must be someone the council trusts to set aside personal preferences during the election process.
    * **Goals of the facilitator role**
        * Clearly documenting and communicating the process and announcing and supporting its execution.
        * Tracking, reviewing, and documenting the effectiveness of the process.
* Review Role Description ([example](https://github.com/rust-lang/rfcs/pull/3392#issuecomment-1505697944)). The role description must contain the following content at a minimum:
    * Goals
    * Time Investment
    * Responsibilities
    * Qualifications
    * Term

### Pre-Meeting Coordination

* Gather nominations
    * The nomination process begins with a public announcement made on public communication channels from the facilitator chosen in the Setup phase. Council representatives should help publicize this announcement to their teams as well.
    * The announcement will specify a date by which nominations must be submitted. This date will be no less than two weeks from the date the announcement goes out, and no more than four weeks.
    * Council representatives collaborate with their subteams to collect nominations on behalf of their branch of the organization tree.
      * Nominations do not have to be members of the Council representative's respective team but must be project members.
    * Subteams can utilize any process they prefer, but we recommend following a similar approach to the process outlined in the "Election Meeting" section below
    * The facilitator may specify a minimum or maximum time period
* Share nominations
    * *Nominations from all teams will be pooled together. In other words, teams do not have to nominate a set of directors as a whole. They may nominate any number of potential directors.*
    * Each team representative must share their team's nominations and the reasoning for their nominations first with the candidates being nominated, and then, for those candidates who consent to be nominated, with the council's selected facilitator.
    * The facilitator must publicly share the pool of all nominations and reasonings at least ten days before the final election meeting.
        * This allows other teams to share feedback or objections about candidates their team didn't initially consider with their representative.
    * This 10-day period is equivalent to the Change Round in the "Election Meeting" step; representatives may change their nominations in advance of the meeting, this does not require restarting the 10-day period.
    * Once nominations are final, the facilitator will share the names of all nominees with the Foundation, who will set up an online election poll.

### Election Meeting

The election meeting is comprised of all members of the Leadership Council who will actively participate in the consensus process as well as the facilitator who will facilitate that process.

* Share nominations
    * Write down nominations first[^1].
    * Use a round format[^2] (e.g. [round format](https://www.sociocracyforall.org/on-rounds/))
    * Nominations must include supporting reasoning 
* Change Round
    * During the change round, every team member will share their current preferred nominees and the reasons for changes from the previous preferred nominees if that applies.
    * Note that the change round is driving around discussing and trying to select the best possible nominee(s) rather than discussing the full set of nominees. De-selecting a nominee from consideration in a given change round does not disqualify the nominee from being selected in future change rounds.
* Facilitator proposes a candidate:
    * Based on gathered data, the facilitator suggests a candidate they believe will receive the group's consent.
* Seek objections to the facilitator's proposal
* Finalize the selection:
    * Discuss and attempt to resolve any objections, if possible.
    * Consent has been reached if the proposed choice has no remaining objections! :tada:
    * If objections persist and the current proposal reaches an impasse, the facilitator should make a new proposal based on the discussion and feedback received.
    * Continue seeking consensus and addressing objections until a satisfactory candidate is selected.
        * Note that this process seeks to produce a candidate everyone is satisfied with and has no objections to. Avoid lengthy debates over preferences not related to objections or unmet requirements.
* Each council member will privately vote in the election poll set up by the Foundation.
* The Foundation will handle:
    * Verifying eligibility.
    * Onboarding new directors.
    * Announcing the new directors ([example](https://foundation.rust-lang.org/news/announcing-the-rust-foundation-s-newest-project-director-carol-nichols/)).
* A council member should help with:
    * Update the private Zulip channel membership (`council-project-directors/private`).
    * Update the director Zulip group `@foundation-project-directors`.
    * Update the [`foundation-board-project-directors`](https://github.com/rust-lang/team/blob/master/teams/foundation-board-project-directors.toml) team.

If for some reason the Council is unable to reach consensus on a group of
candidates (for example, the Council finds blocking objections to all
candidates), the Council will postpone the election process to give a chance to
troubleshoot and find an approach that is more likely to be successful. We do
not specify how this will happen, but the council would likely convene a
subcommittee to work on the issue and report back to the council.

### Conflicts of Interest

The Council will follow the policies defined in the [Leadership Council
RFC][rfc3392] for handling conflicts of interest. One potential source of
conflicts of interest is if a Council member is nominated as a candidate for the
Project Director role.

[rfc3392]: https://rust-lang.github.io/rfcs/3392-leadership-council.html
### FAQ

#### Why is there no step where we initially require that people consent to be nominated?

One of the goals of this policy is to create opportunities for new leadership. We want to create an environment encouraging people to step up into power. Sometimes the confidence and faith of a group can give people the confidence they need to consent to being selected. Thus, we do not require people to ask the nominee for consent in the Pre-Meeting Coordination phase. We will, however, explicitly ask each candidate before considering them during the Election Meeting.

## What if the election results differ from the consensus process?

This technically can happen, if the Council members all express agreement on a set of candidates and then a majority of them vote differently. In this scenario the vote would be binding. However, it is also clear that the outcome does not reflect the expressed preferences of the Project.

There are several possibilities for how to proceed in this case. As one possibility, the teams whose representatives voted against the consensus may decide their representative is no longer trustworthy to represent them and thus appoint a new Council Representative. The new Council could then choose to vote again to replace the Project Directors. Both Council Members and Project Directors can be replaced at any time, even if this does not line up with the usual term rotation.

[^1]: During the nomination round, it is incredibly tempting to just go with the group energy, especially when you are speaking late in the Round. Writing down your nomination will encourage you to share your genuine nomination without getting swayed too soon (or not at all). So often, the best ideas are the ones that seem peripheral at first.
[^2]: A round is a conversation format where everyone speaks, one by one, until everyone in the group has spoken. It starts with the facilitator asking a specific question or prompt to one person and then proceeds one by one until everyone has shared. In a round, people can share their initial reactions and reflections on what has been stated before them. It is a way to ensure that everyone's voice is heard equally, and it gives maximum input both from individuals and group wisdom.
