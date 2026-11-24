# MEH GTM Engine

## Run the prototype

Open index.html from the source repository, or open the published demo at https://meh-gtm-engine.lovable.app/. Generate an editable buyer profile from the offer, then select Find live hiring signals to query public Greenhouse boards. The curated examples work offline and all evidence links open their original public sources.

## System design

Live discovery reads up to five user-selected Greenhouse boards through their public API. It filters published job titles for AI, cloud and data signals and checks descriptions for explicit contract work. Other relevant roles remain discovery questions. Results carry the original posting link, and a failed board does not suppress results from successful boards. Procurement matching uses the curated Tyrone example.

Automatic company discovery searches public Hacker News comments through the Algolia HN Search API using up to three buyer-profile capabilities and their search aliases. It extracts Greenhouse board links, skips manually selected boards, and checks up to twelve candidate boards against the current Greenhouse feeds. A board appears only when the engine finds a current role with matching evidence. Cards link both to the hiring post used to discover the board and to the live job listing used to qualify the signal. This is bounded to companies discussed on Hacker News with identifiable Greenhouse links.

The profile generator uses transparent rules to suggest a buyer role, segment hypothesis, capability keywords, and engagement priority from the offer. Capability matches contribute up to 50 points, compatible affirmative engagement evidence contributes 35, and a sourced contact role contributes 15. The reviewer can edit priorities and run discovery again to rank results against the updated criteria. The score ranks the evidence available to the demo. Segment and buyer role are hypotheses, and purchase intent and eligibility require confirmation.

The Arionkoder live board has a curated contact lookup from the company's public leadership page for its team augmentation lead. This verifies a published role and leaves ownership of a particular opening and buying authority unconfirmed. Other live boards retain an inferred buyer role until sourced. Offer changes clear the displayed discovery results before a new search. Venue-marketplace offers generate event-planner criteria, but discovery still reads hiring signals and does not match venue inventory or verify live event demand.

The browser holds an editable product offer, buyer role and discovery filter. The discovery stage evaluates three curated public evidence records using deterministic rules. An explicit contract specialist signal routes to an individual contributor. An explicit accountable provider signal routes to an MSP. Other signals route to a discovery question. The Town of Tyrone procurement demonstrates provider ownership and falls outside the proposed mid-market segment. Its RFP names the Town Manager as proposal addressee. EMPIST's directory listing supports service overlap, while the addendum establishes gaps to verify before treating it as eligible.

The review screen displays a relationship chain from account through public signal and inferred buying role to MEH service. The current implementation renders this chain from fixture records. A full pipeline would persist Company, Person, Signal and Service nodes and query their relationships. Person records should be linked to their own sources before being labeled verified.

The engine drafts outreach from the selected evidence, offer and route. For Tyrone, it drafts an internal qualification note because follow-up belongs in the published procurement process. Selecting a card or approving its draft records the exact approved text in a single batch queue. Editing an approved draft removes just that draft from the queue. The batch button delivers each approved snapshot to the visible local test inbox and changes the corresponding pipeline stage. Rejection excludes the account from subsequent discovery runs in the current session and records an audit entry. Inbox, pipeline and audit state reset on reload.

## Two-minute demo outline

- Generate an editable buyer profile from MEH’s offer.
- Run live discovery. Show the ranking, contract signal, and source for the top Arionkoder posting.
- Open the lead. Show the contact source and the question that still needs to be answered.
- Approve the same lead’s draft and show the local test inbox, pipeline, and human and engine audit entries.
- Point to the curated Tyrone → EMPIST case for the managed service provider path.

## Submission and known limits

The live app and public source repository are available at https://meh-gtm-engine.lovable.app/ and https://github.com/bulatao/meh-gtm-engine. The walkthrough is submitted separately. Procurement discovery, broad contact enrichment, a graph database, durable pipeline state, external delivery and bonus integrations remain outside this prototype.
