# Issue tracking

The issue tracker for the Leadership Council is located at <https://github.com/rust-lang/leadership-council/issues/>. It is primarily used for:

* Open Council and Committee tasks.
* Questions for the council.
* Proposals for new policy and process.

Anyone is welcome to submit issues and to participate in discussion. Alternatively, you may consider bringing up questions and ideas on the [Leadership Council Zulip stream][zulip].

If you want to bring up a security issue, please do not open a public issue on GitHub. Instead, we ask you to refer to Rust's [security policy].

If you have a private matter to bring to the Council, please email <council@rust-lang.org>.

[zulip]: https://rust-lang.zulipchat.com/#narrow/stream/392734-council
[security policy]: https://www.rust-lang.org/security.html

## Issue labels

[Issue labels] are used to help categorize issues and to communicate the status.

Similar to the rest of the Rust-lang project, we use prefixes and colors to indicate the kind of label:

* `A-*` — labels for different **areas** or topics.
* `C-*` — labels for issues belonging to a specific **Committee**.
* `P-*` — labels to denote the **priority**.
* `S-*` — labels for tracking the **status** of an issue. It is recommended for almost all issues to have a status label to communicate what its status is.

Council members may create new labels as they find useful.

[issue labels]: https://github.com/rust-lang/leadership-council/labels

## Triage

### Inbound triage

The entire Council is responsible for answering questions and moving issues out of the `S-triage` state. Ultimately the Librarians should ensure that issues are eventually triaged or to raise awareness of an issue to a Committee or the Council in order to find the next steps. This can be done informally, such as on the issue itself or in Zulip, or more formally such as being proposed for the sync meeting agenda (though that should only be done for rare cases where synchronous discussion and decision of the whole Council is needed).

Once `S-triage` is removed, if the issue isn't closed, one of the other status labels should be applied. If the issue is related to a specific Committee or area, those specific labels should be added. If more information is needed, the triager should ask for what is needed and set `S-needs-info`.

### Status triage

All Council Members are expected to participate in keeping issues up-to-date with their latest status. However, diffusion of responsibility can mean things don't get updated. The Librarians are responsible as a backstop for this:

* After approximately 3 months of inactivity, a Librarian should check that the issue accurately reflects its current status. If an issue needs to be redirected or delegated to someone to make it move forward, they should see if there is an obvious candidate.
* After approximately 1 year of inactivity, a Librarian should again check the issue accurately reflects its current status. If it seems like it is unlikely for the issue to get resolved in the foreseeable future, or seems to be indefinitely blocked on an outside party, they should post a comment to that effect (or ask for clarification) and notify that the issue will be closed during the next triage round if there is no further comment. A closed issue does not mean that it has been rejected, just that it is not active and is unlikely to be addressed. It can always be reopened if something changes. These issues will get the `S-closed-inactive` label to indicate that it was closed for this purpose.

### Reevaluation

If an issue author feels like their issue has been mis-triaged, they are encouraged to ask about it, either by starting a [Zulip thread][zulip] and tag the Council member, or following up on the issue. Usually this happens due to insufficient information on either side, so further discussion may help clear things up.
