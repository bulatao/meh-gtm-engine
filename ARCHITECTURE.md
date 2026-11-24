# MEH GTM Engine

## Run the prototype

Open index.html from the source repository, or open the published demo at https://meh-gtm-engine.lovable.app/. Generate an editable buyer profile from the offer, then select Find live hiring signals to query public Greenhouse boards. The curated examples work offline and all evidence links open their original public sources.

## System design

Live discovery reads up to five user-selected Greenhouse boards through their public API. It filters published job titles for AI, cloud and data signals and checks descriptions for explicit contract work. Other relevant roles remain discovery questions. Results carry the original posting link, and a failed board does not suppress results from successful boards. Procurement matching uses the curated Tyrone example.

The profile generator uses transparent rules to suggest a buyer role, segment hypothesis, capability keywords, and engagement priority from the offer. Capability matches contribute up to 50 points, compatible affirmative engagement evidence contributes 35, and a sourced contact role contributes 15. The reviewer can edit priorities and rerank current results without querying the feeds again. The score ranks the evidence available to the demo. Segment and buyer role are hypotheses, and purchase intent and eligibility require confirmation.

The Arionkoder live board has a curated contact lookup from the company's public leadership page for its team augmentation lead. This verifies a published role and leaves ownership of a particular opening and buying authority unconfirmed. Other live boards retain an inferred buyer role until sourced.

The browser holds an editable product offer, buyer role and discovery filter. The discovery stage evaluates three curated public evidence records using deterministic rules. An explicit contract specialist signal routes to an individual contributor. An explicit accountable provider signal routes to an MSP. Other signals route to a discovery question. The Town of Tyrone procurement demonstrates provider ownership and falls outside the proposed mid-market segment. Its RFP names the Town Manager as proposal addressee. EMPIST's directory listing supports service overlap, while the addendum establishes gaps to verify before treating it as eligible.

The review screen displays a relationship chain from account through public signal and inferred buying role to MEH service. The current implementation renders this chain from fixture records. A full pipeline would persist Company, Person, Signal and Service nodes and query their relationships. Person records should be linked to their own sources before being labeled verified.

The engine drafts outreach from the selected evidence, offer and route. For Tyrone, it drafts an internal qualification note because follow-up belongs in the published procurement process. Human approval records the exact draft in memory. Editing invalidates approval, and local delivery checks the approved text again before adding it to the visible test inbox and changing the pipeline stage. Rejection excludes the account from subsequent discovery runs in the current session and records an audit entry. Inbox, pipeline and audit state reset on reload.

## Two-minute demo outline

- **0:00–0:25**. Introduce MEH as the first prospective GTM Engine customer. Run fixture discovery from its offer and an IT or AI delivery buyer role.
- **0:25–0:55**. Compare Arionkoder’s contract opening, Tyrone’s managed IT procurement, and Future’s ambiguous AI hiring signal.
- **0:55–1:25**. Open Tyrone. Show the source, proposal addressee, EMPIST’s overlapping capabilities, and the qualifications still to confirm.
- **1:25–1:50**. Approve the internal review draft, deliver it to the local test inbox, and show the approval and delivery in the audit trail.
- **1:50–2:10**. Reject a weak match and rerun discovery. Show that the rejected account stays out for the session.

## Submission and known limits

The live app and public source repository are available at https://meh-gtm-engine.lovable.app/ and https://github.com/bulatao/meh-gtm-engine. The walkthrough is submitted separately. Procurement discovery, broad contact enrichment, a graph database, durable pipeline state, external delivery and bonus integrations remain outside this prototype.
