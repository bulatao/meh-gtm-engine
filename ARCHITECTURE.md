# MEH GTM Engine

## Run the prototype

Open MEH GTM Engine.html in a desktop browser. The demo examples work offline. Select Find live hiring signals to query public Greenhouse boards over the internet. The evidence links open the original public sources.

## System design

Live discovery reads up to five user-selected Greenhouse boards directly through their public API. It filters published job titles for AI, cloud and data signals, then checks descriptions for an explicit contract role. Other relevant roles remain discovery questions. Results carry the original posting link, and a failed board does not suppress results from successful boards. Procurement matching uses the curated Tyrone example.

The browser holds an editable product offer, buyer role and discovery filter. The discovery stage evaluates three curated public evidence records using deterministic rules. An explicit contract specialist signal routes to an individual contributor. An explicit accountable provider signal routes to an MSP. Other signals route to a discovery question. The Town of Tyrone procurement demonstrates provider ownership and falls outside the proposed mid-market segment. Its RFP names the Town Manager as proposal addressee. EMPIST's directory listing supports service overlap, while the addendum establishes gaps to verify before treating it as eligible.

The review screen displays a relationship chain from account through public signal and inferred buying role to MEH service. The current implementation renders this chain from fixture records. A full pipeline would persist Company, Person, Signal and Service nodes and query their relationships. Person records should be linked to their own sources before being labeled verified.

The engine drafts outreach from the selected evidence, offer and route. For Tyrone, it drafts an internal qualification note because follow-up belongs in the published procurement process. Human approval records the exact draft in memory. Editing invalidates approval, and local delivery checks the approved text again before adding it to the visible test inbox and changing the pipeline stage. Rejection excludes the account from subsequent discovery runs in the current session and records an audit entry. Inbox, pipeline and audit state reset on reload.

## Two-minute demo outline

- **0:00–0:25**. Introduce MEH as the first prospective GTM Engine customer. Run fixture discovery from its offer and an IT or AI delivery buyer role.
- **0:25–0:55**. Compare Arionkoder’s contract opening, Tyrone’s managed IT procurement, and Future’s ambiguous AI hiring signal.
- **0:55–1:25**. Open Tyrone. Show the source, proposal addressee, EMPIST’s overlapping capabilities, and the qualifications still to confirm.
- **1:25–1:50**. Approve the internal review draft, deliver it to the local test inbox, and show the approval and delivery in the audit trail.
- **1:50–2:10**. Reject a weak match and rerun discovery. Show that the rejected account stays out for the session.

## Remaining submission work

Extend live discovery to procurement notices and verify contacts for new leads. Add a graph store, durable pipeline state and external controlled-inbox delivery. Integrate Band Desktop to demonstrate real planner, builder and reviewer handoffs. Flexprice and Snyk are separate optional integrations. Prepare a public source repository and record the actual walkthrough after the submission workflow is verified.
