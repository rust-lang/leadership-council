# The Rust Project Leadership Council

This repo is the home for documentation related to the [Leadership Council][governance page] for the Rust Programming Language Project (a.k.a. the Council).

The Council was established by [RFC #3392][rfc]. The RFC describes the Council at a high-level as the following:

> This RFC establishes a Leadership Council as the successor of the core team and the new governance structure through which Rust Project members collectively confer the authority to ensure successful operation of the Project. The Leadership Council delegates much of this authority to teams (which includes subteams, working groups, etc.) who autonomously make decisions concerning their purviews. However, the Council retains some decision-making authority, outlined and delimited by this RFC.
>
> The Council [is] composed of representatives delegated to the Council from each top-level team.
>
> The Council is charged with the success of the Rust Project as a whole. The Council will identify work that needs to be done but does not yet have a clear owner, create new teams to accomplish this work, hold existing teams accountable for the work in their purview, and coordinate and adjust the organizational structure of Project teams.

For more information on *why* the Council exists, please refer to [the supplementary material to RFC #3392][motivation] that addresses this topic.

[governance page]: https://www.rust-lang.org/governance/teams/leadership-council
[motivation]: https://rust-lang.github.io/rfcs/3392-leadership-council/motivation.html
[rfc]: https://rust-lang.github.io/rfcs/3392-leadership-council.html

## Resources

### Zulip

If you'd like to participate in conversations about governance or otherwise interact with the Council in some form, you can find the Council on the [#council stream on Zulip][zulip].

The Council may create additional streams for specific projects. Consult the stream list for any that start with "council".

There are several private streams reserved for topics that must be kept private. See the [private decision guidelines][private-decision] for the types of discussions that may need to be private. Council members should avoid the private channels unless absolutely necessary. These channels are:

* `#council/private` — Private discussions among the council.
* `#council-mods-private` — Private discussions involving both the council and moderation teams.
* `#foundation-council-private` — Private discussions involving both the council and the Foundation.

[zulip]: https://rust-lang.zulipchat.com/#narrow/stream/392734-council
[private-decisions]: https://forge.rust-lang.org/governance/council.html#decisions-that-the-council-must-necessarily-make-privately

### Council Meetings

The Council has synchronous meetings to discuss topics and make decisions. See [`procedures/synchronous-meetings.md`] for more information.

[`procedures/synchronous-meetings.md`]: https://github.com/rust-lang/leadership-council/blob/main/procedures/synchronous-meetings.md

### HackMD

The Council has a public HackMD workspace at <https://hackmd.io/team/rust-leadership-council>. This workspace provides a home for Council members to collaborate and create draft documents. More permanent documentation should go in this repository or the Rust Forge.

Since this HackMD workspace is using the free service, it does not support private documents. If you need to draft a private document, create it in your personal workspace and use private channels to share the link.

### Governance documentation

The current set of policies that govern the Council are documented on the Forge in the [Leadership Council chapter][forge-council]. When governance policy changes are approved (via the RFC process), the Forge governance documentation should be updated to reflect those changes.

[forge-council]: https://forge.rust-lang.org/governance/council.html

### Committees

The Council may create committees to delegate work or decision authority. Committee charters and membership are tracked in the [`committees/`] directory. The [`TEMPLATE.md`] file in that directory contains a starter template for defining a committee. A committee can be created with the full consensus of the Council.

[`committees/`]: https://github.com/rust-lang/leadership-council/tree/main/committees
[`TEMPLATE.md`]: https://github.com/rust-lang/leadership-council/blob/main/committees/TEMPLATE.md

### Issue and work tracking

The GitHub issue tracker at <https://github.com/rust-lang/leadership-council/issues> is used for tracking work items, a backlog of tasks, and questions from the public. More information about the issue tracker may be found in [`procedures/issues.md`].

[`procedures/issues.md`]: https://github.com/rust-lang/leadership-council/blob/main/procedures/issues.md

## License

Content in this repository is licensed under the [MIT license](LICENSE-MIT) and the [Apache license 2.0](LICENSE-APACHE).
