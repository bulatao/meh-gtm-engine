# MEH GTM Engine

HackwithBay 4.0 prototype for MultiExpert Hub. It evaluates buying signals and routes a prospect toward an individual contributor, an MSP, or a discovery question.

## Run or host

Published demo: https://meh-gtm-engine.lovable.app

Open `index.html` directly in a current desktop browser. A static host can serve the same file at the root. The curated demo works offline. Live discovery needs internet access to the public Greenhouse Job Board API. This version has no dependencies, build step, or API keys.

## Reviewer walkthrough

1. Review the prefilled offer or replace it. Select **Generate buyer profile from offer** immediately below it to populate the blank profile fields, then **Discover companies and hiring signals**. Check both source links and the ranking explanation. **Other discovery options** contains the curated examples and manual board scan.
2. Select **Run demo examples**, then **Review match** under the Town of Tyrone. Review the evidence and EMPIST's fit and eligibility gaps.
3. Approve the internal draft and send it to the local test inbox. Verify that the exact draft appears and the pipeline records delivery.
4. Reject a weak match and confirm discovery excludes it for the browser session.

The local test inbox does not deliver external mail. Public signals do not confirm buying intent or provider availability. Procurement is a curated example and live discovery currently scans Greenhouse hiring data. Session data resets on reload.

See `ARCHITECTURE.md` for design and the demo recording outline.
