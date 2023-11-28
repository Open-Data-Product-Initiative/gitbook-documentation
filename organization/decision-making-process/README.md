---
description: Various decision-making processes
---

# Decision-making processes

## New Release

Technical Steering Committee (TSC) decides when a new release is needed since they lead the specification development and have the best knowledge of changes and maturity of the development version.&#x20;

### Alignment phase

1. TSC creates a proposal for a new release for the Strategy Group (SG) to review. In the proposal, TSC lists the changes and expected added value for consumers. The proposal also contains information is this minor or major release. The proposal contains also planned roadmap to release with timetable.  Patches can be pushed to the production version without SG review.&#x20;
2. The release proposal is discussed at the SG meeting and possible comments will be provided to TSC to consider. SG reviews the release proposal to align it with the strategy, which SG is responsible for.&#x20;
3. SG can stop the release process but the reasons must be very solid and most commonly additional discussion is needed between TSC and SG. We seek always alignment, not power struggles. &#x20;

### Release phase

After SG's review, TSC starts executing the accepted and aligned release plan. The default minimal process contains following steps:

1. A Release Candidate from development version is created and development version is closed. Stopping development is needed, so that focus can be given for the release. Release the RC to Github as repository.&#x20;
2. RC is open for comments for 14 days
   1. After commenting TSC processes the feedback.&#x20;
   2. If changes are needed before release, then after implementing the changes, a new Release Candidate is published (RC1). Again commenting is open for 14 days.&#x20;
3. The above is repeated until no changes are requested and we have strong alignment about the new release.&#x20;
4. Finally, RC is published as a new version of ODPS.&#x20;
5. After this new development version is derived from the release and new development version is opened for pull requests.&#x20;
6. Opendataproducts.org website is updated regarding the versions part to match the current situation and versions.&#x20;
