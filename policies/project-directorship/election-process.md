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

## Procedure

### Setup

* The council selects a facilitator by consent:
    * Any team member can suggest a facilitator or volunteer themselves.
    * The facilitator must not be a nominee in the election and must be someone the council trusts to set aside personal preferences during the election process.
    * **Goals of the facilitator role**
        * Clearly documenting and communicating the process and announcing and supporting its execution.
        * Tracking, reviewing, and documenting the effectiveness of the process.
* Review the [PD role description](https://github.com/rust-lang/leadership-council/blob/main/roles/rust-foundation-project-director.md).

The facilitator role is time-consuming and may be better suited for someone already being paid to work on the Project. A Project Manager is a good option, as this role fits well within their responsibilities.

The Council can also ask the Foundation to provide a staff member, but that should be done well in advance (3-4 months to make sure they can find someone who will have the time).

### Pre-Meeting Coordination

* Gather nominations
    * The nomination process begins with a public announcement made on public communication channels from the facilitator chosen in the Setup phase. Council representatives and team leads should help publicize this announcement to their teams as well. Past examples:
        * [Inside Rust Blog](https://blog.rust-lang.org/inside-rust/2025/08/20/electing-new-project-directors-2025/)
        * [Zulip](https://rust-lang.zulipchat.com/#narrow/channel/392734-council/topic/2025.20project.20director.20elections/near/535321402)
        * Emailing `all@rust-lang.org`
    * The announcement will explicitly spell out the "Affiliation Limits" section below.
    * The announcement will specify a date by which nominations must be submitted. This date will be no less than two weeks from the date the announcement goes out, and no more than four weeks.
    * Council representatives collaborate with their subteams to collect nominations on behalf of their branch of the organization tree.
      * Nominations do not have to be members of the Council representative's respective team but must be project members.
    * Subteams can utilize any process they prefer, but we recommend following a similar approach to the process outlined in the "Election Meeting" section below
    * The facilitator should reach out directly to team leads to:
        * Bring the process to their teams.
        * Collect nominations from their members.
        * NOTE: The leads are not tasked with nominating candidates directly (though they can do so, just like any other Project member).
    * The facilitator may specify a minimum or maximum time period.
	* It is recommended to start the process at least 2 months before the board meeting attended by the new PDs.
* Share nominations
    * *Nominations from all teams will be pooled together. In other words, teams do not have to nominate a set of directors as a whole. They may nominate any number of potential directors.*
    * Each team representative must share their team's nominations and the reasoning for their nominations first with the candidates being nominated, and then, for those candidates who consent to be nominated, with the council's selected facilitator.
    * Each consenting candidate must write a statement on their candidacy.
      * The facilitator must clarify that these statements will be made public.
      * For reference, here are the [2025](https://hackmd.io/@rust-leadership-council/S1WrrVY_ex) and [2024](https://hackmd.io/@rust-leadership-council/B1aNREWZye) candidate statements.
    * The facilitator must publicly share the pool of all nominations, statements, and reasonings at least ten days before the final election meeting.
        * This allows other teams to share feedback or objections about candidates their team didn't initially consider with their representative.
        * The facilitator will explicitly reach out to team leads, existing PDs, and the Council for feedback.
    * This 10-day period is equivalent to the Change Round in the "Election Meeting" step; representatives may change their nominations in advance of the meeting, this does not require restarting the 10-day period.
    * The facilitator will share the names of all nominees with the Foundation, who will set up an online election poll.
        * In the past rounds, the poll was set up by @BecRumbul.
        * The poll **doesn't allow changing one's vote** after it's cast. The Council should verify access, but they must *only cast the vote at the appropriate time* during the Election Meeting.


### Election Meeting Preparation

The election meeting is comprised of all members of the Leadership Council who will actively participate in the consensus process as well as the facilitator who will facilitate that process.

The facilitator schedules the meeting. This is typically done at the same time and day of the week as the Council meeting, but on an off week (i.e. Friday when there's no scheduled Council meeting). In 2025, the meeting took 2.5 hours, compared to 1.5 in previous years. The facilitator must share this expectation and should consider scheduling it earlier, if possible.

If a Council member is unable to attend the Election Meeting or needs to recuse themself, the team they represent will select another member to act in their stead.

The facilitator will create a HackMD document containing:

* The candidates
* Their statements
* Feedback received
* A "Discussion" section to capture everyone's thoughts on each candidate
* A "Preferences" section with a table
* A "Selection" section

The Preferences section looks like this:

`-1`: I have objections
`0`: Not my choice, but no objections
`1`: I prefer this candidate

|      | Candidate 1 | Candidate 2 | Candidate 3 | Candidate 4 | Candidate 5 |
|------|-------------|-------------|-------------|-------------|-------------|
| LC A | 0           | +1          | +1          | 0           | -.5         |
| LC B | +1          | 0.5         | +1          | -1          | +1          |
| LC C | +1          | -.5         | 0           | +.5         | +1          |
| LC E | 0           | -.5         | 0           | +.5         | +1          |
| LC F | +1          | -.5         | +1          | +.5         | +1          |
| LC G | +1          | -.5         | 0           | +.5         | +1          |
| LC H | +1          | -.5         | 0           | +.5         | +1          |
|------|-------------|-------------|-------------|-------------|-------------|
| Sum  | +5          | -1          | 3           | +1.5        | +5.5        |

The first column lists all the LC members and stand-ins who cast the votes. The first row lists all the PD candidates.

Each Council member will share their (non-binding) preference on each candidate in isolation. The actual discussion and election process is described in the "Election Meeting" section below.

NOTE: The facilitator must ensure that the document is accessible to every voting member and *no one else*. In particular, if an existing Council member is among the candidates, the document cannot be created under the Leadership Council HackMD organisation.

For example, in 2025, the facilitator created a document in their personal account, set the "Read" and "Write" Note permissions to "Signed-in users" and took care to only share the link with the voting members. After the meeting, they set the permission to "Only me".

This is to work around the fact that our free HackMD accounts don't allow sharing a private note with more than three other people. The facilitator should investigate other solutions ahead-of-time.


### Election Meeting

* Share nominations
    * Write down nominations first[^1].
    * Use a round format[^2] (e.g. [round format](https://www.sociocracyforall.org/on-rounds/)).
    * Nominations must include supporting reasoning .
* Change Round
    * During the change round, every team member will share their current preferred nominees and the reasons for changes from the previous preferred nominees if that applies.
    * Note that the change round is driving around discussing and trying to select the best possible nominee(s) rather than discussing the full set of nominees. De-selecting a nominee from consideration in a given change round does not disqualify the nominee from being selected in future change rounds.
* Facilitator proposes a candidate selection:
    * Based on gathered data, the facilitator suggests a set of candidates they believe will receive the group's consent.
    * The proposal should contain the full set of proposed PDs rather than selecting them one by one.
      * That way, the Council can consider any potential conflicts and related concerns within the group as a whole.
* Seek objections to the facilitator's proposal
* Finalize the selection:
    * Discuss and attempt to resolve any objections, if possible.
    * Consent has been reached if the proposed choice has no remaining objections! :tada:
    * If objections persist and the current proposal reaches an impasse, the facilitator should make a new proposal based on the discussion and feedback received.
    * Continue seeking consensus and addressing objections until a satisfactory candidate is selected.
        * Note that this process seeks to produce a candidate everyone is satisfied with and has no objections to. Avoid lengthy debates over preferences not related to objections or unmet requirements.
* Each council member will privately vote in the election poll set up by the Foundation.
    * The vote happens during the meeting itself.
* After the meeting, the Facilitator will confirm with the Foundation whether:
    * All the votes were cast.
    * The results match the final selection.
    * The votes were unanimous.
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
subcommittee to work on the issue and report back to the Council.

### Affiliation Limits

There can be **at most one** Project Director employed by a company that's a [*corporate member* of the Foundation](https://rustfoundation.org/members/)[^3][^4].

Affiliation limits only apply to companies that are corporate (Platinum, Gold, or Silver) members.

### Conflicts of Interest

The Council will follow the policies defined in the [Leadership Council
RFC][rfc3392] for handling conflicts of interest.

[rfc3392]: https://rust-lang.github.io/rfcs/3392-leadership-council.html

One potential source of conflicts of interest is if a Council member is nominated as a candidate for
the Project Director role. In that case, the team the Council member represents will select another
representative who will participate in the election process and cast the vote.

### FAQ

#### Why is there no step where we initially require that people consent to be nominated?

One of the goals of this policy is to create opportunities for new leadership. We want to create an environment encouraging people to step up into power. Sometimes the confidence and faith of a group can give people the confidence they need to consent to being selected. Thus, we do not require people to ask the nominee for consent in the Pre-Meeting Coordination phase. We will, however, explicitly ask each candidate before considering them during the Election Meeting.

## What if the election results differ from the consensus process?

This technically can happen, if the Council members all express agreement on a set of candidates and then a majority of them vote differently. In this scenario the vote would be binding. However, it is also clear that the outcome does not reflect the expressed preferences of the Project.

There are several possibilities for how to proceed in this case. As one possibility, the teams whose representatives voted against the consensus may decide their representative is no longer trustworthy to represent them and thus appoint a new Council Representative. The new Council could then choose to vote again to replace the Project Directors. Both Council Members and Project Directors can be replaced at any time, even if this does not line up with the usual term rotation.

[^1]: During the nomination round, it is incredibly tempting to just go with the group energy, especially when you are speaking late in the Round. Writing down your nomination will encourage you to share your genuine nomination without getting swayed too soon (or not at all). So often, the best ideas are the ones that seem peripheral at first.
[^2]: A round is a conversation format where everyone speaks, one by one, until everyone in the group has spoken. It starts with the facilitator asking a specific question or prompt to one person and then proceeds one by one until everyone has shared. In a round, people can share their initial reactions and reflections on what has been stated before them. It is a way to ensure that everyone's voice is heard equally, and it gives maximum input both from individuals and group wisdom.
[^3]: Project Director [Requirements and Eligibility](../../roles/rust-foundation-project-director.md#requirements-and-eligibility)
[^4]: [Section 4.3(g)](https://rustfoundation.org/policy/bylaws/#section-4.3-nomination%2C-election-and-term-of-office-of-directors) of the Foundation Bylaws.
