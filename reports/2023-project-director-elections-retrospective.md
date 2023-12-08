# 2023 Project Director Elections Retrospective

One of the goals for the Project Director Election Process Committee is to "[Track, review, and document the effectiveness of the process][goals]."
Now that we've completed the election process, we'd like to reflect on how things went and make recommendations for future elections.

[goals]: ../committees/project-director-election-process.md

## Summary

We were able to elect three new Project Directors and we did so in time to have them attend the first Board meeting after the outgoing directors' terms ended.
These were chosen from a large pool of candidates that were nominated from across the project.

Going forward, we'd recommend working to improve the following areas:

1. **Candidate Eligibility and Requirements** - We had late-breaking questions around how "employment" is interpreted for the purposes of employment limits and around the legal requirements for candidates to disclose their names. At a minimum, we need to clearly document these requirements. We should also consider whether changes to these requirements are possible and desirable, as they significantly constrain who is able to serve in this role and makes it difficult to achieve other goals around diversity.
2. **Scheduling** - The schedule we followed was tight and didn't have a lot of room for slipping. It was complicated by the fact that several key milestones in the process lined up with RustConf and EuroRust.
3. **Process Refinement** - There were some minor ways we deviated from the documented election process. For example, the document says each team would ask their nominees for consent before sending them to the Council, but instead the elections facilitator did this task. We should update the documentation to accurately reflect the process.

## Goal Evaluation

The election process procedure outlines several goals for the process.
We will now go through each of these goals and evaluate how well we achieved them.

### Select Candidates Who Fulfill the Outlined Candidate Criteria

> * Select candidates who fulfill the outlined candidate criteria in the [role description document](../roles/rust-foundation-project-director.md), focusing on new leadership and diverse perspectives rather than solely prioritizing the best candidate.
>    * Strive for tolerance and inclusivity by prioritizing selecting candidates that everyone can accept over selecting the first choice for only a subset of people.

One challenge here was that the criteria was under-specified during the election process.
This was a conscious choice in order to achieve the time-efficiency goal, so we chose to go with a minimal role description that we could refine over time rather than blocking on a perfect description.
This mean the role description was actually a PR still under discussion for much of the process.

This caused some challenges for nominees who had to decide whether to accept the nomination since the scope of the responsibilities was not entirely clear.

There were also unclear eligibility criteria, particularly around employment limits.

One strength here is that several of the nominees were outside of the set of well-known Rust project leaders, which suggests the nomination process was successful in helping to bring more people into project organization and leadership roles.

### Conduct the Selection Process in a Time-efficient Manner

To fully evaluate this, we need to know what we mean by time-efficient.

One measure is the number of calendar days that it took to do the process.
If we go by the blog posts that announced the beginning of the process and the end of the process, this took from August 30 until October 19, or 50 days.
We needed to allow at least two weeks (14 days) for the nomination phase, and 10 days for the feedback phase, so the absolute minimum possible time would be 24 days.
In practice, it's helpful to have some slack time between these phases, and we also needed time to coordinate the election meeting itself.
Note that these 50 days do not include the time to design and plan for the process ahead of time.
In the future, there should be less preplanning needed because we will not be designing the process from scratch.

One reasons slack time in the schedule was helpful was that we neglected to plan time for nominees to consider whether to accept their nomination, and also time to confirm with the candidates who were selected.
Going forward we should allow for this, because being willing to serve as a Project Director is a consequential decision that deserves adequate time to consider.

Another measure of time efficiency is the time it took the people involved in the process to coordinate and do each of the steps.
The role of Project Director Facilitator took a significant amount of time.
It would be nice to reduce the time requirement, perhaps by subdividing the role.

Relating to scheduling, we also need to consider scheduling constraints outside the election process itself.
For example, candidate nominations closed on the last day of RustConf, and we were working on the blog post announcing the results of the election during the week of EuroRust.
Going forward, we should consider major conferences of broad interest to the community and avoid scheduling election milestones during those times.

It's not clear how best to think about time efficiency.
In some ways, we spent a reasonable amount of time.
Still, the process seemed more time-consuming than expected.
It's likely that this is primarily the result of under-estimating the time it takes to do Project Director Elections well.

### Incorporate Input from a Wide Range of Stakeholders Across the Entire Rust Project

We feel overall we did well on this goal.
The steps in the process were widely communicated.
The nomination process being done per-team helped to ensure we had good coverage across the Rust project.
During the feedback phase, we felt like we heard from a variety of people in the project.

### Ensure a Diverse Pool of Qualified Candidates for Selection

We had nine qualified candidates nominated.
Along several dimensions, diversity was rather low.
It's hard to quantify this exactly because we did not collect demographic information about the nominees.

While not usually considered diversity, given the impact of employment limits, we should perhaps consider having nominees from a diverse set of employers as part of this goal.

One way to improve this going forward is to emphasize the desire to have a diverse set of candidates in our call for nominees.
For example, we could include a statement like "the Rust Project aims to have diverse leadership that represents the perspectives of all members of the Rust community. We encourage you to consider nominees that can bring new backgrounds and perspectives to Rust leadership."

### Create a Psychologically Safe Environment that Values Minority Perspectives

> * Create a psychologically safe environment that values minority perspectives and encourages positive feedback, encouragement, and tolerance rather than personal preference or criticism.

It's not really clear how best to evaluate this, and this is something we should pay attention to going forward.
One option is to survey those involved using something a process like is described [here][psych-safety].
We believe it would be best to integrate this into future election projects, or even project operations as a whole, rather than restroactively sending out a survey about the elections process at this point.

[psych-safety]: https://psychsafety.co.uk/measure-psychological-safety/

### Ensure Participants Feel Positive About Their Interactions and the Execution of the Process

There is definitely room to improve here, as several participants had a decidedly negative experience.

While this won't address all of the ways in which people had a negative experience, some of this was the result of having a new process that was changed midstream several times.
The next time around, we will be using an existing process, although there will be adjustments made.
We expect we will be able to give participants much clearer expectations in the future.

Several other negative experiences are likely rooted in other pre-existing conflicts within the Rust community, so we encourage the Leadership Council to prioritize ways to uncover and address these conflicts.

## Ensure the Process Is Compliant with Rust Foundation Bylaws and Delaware Corporation Law

As far as we know, we did this.
There were some ways in which this was challenging.
For example, the bylaws require that we do an election to select Project Directors, but the Rust project strongly prefers consent over voting.

One particular challenge here was that we were advised by Foundation legal counsel that Directors would need to provide their legal name on public IRS filings on behalf of the Foundation.
This requirement deters trans people from serving in the Project Director role because this name may not match the name they go by, and having that name made public can lead and has led to harassment.
Furthermore, the concept of "legal name" does not exist in the same way across all jurisdictions that cover members of the Rust community.
