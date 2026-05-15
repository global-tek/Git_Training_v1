# Workshop 05 - Regulated Change Control

## Scenario
Teams in a regulated environment must demonstrate approvals, separation of duties, and complete audit trails.

## Objective
Design an SCM workflow that satisfies compliance without halting delivery.

## Focus Areas
- Protected branches and required reviewer roles
- Signed commits and signed tags
- Linking changes to tickets and approval records
- Immutable release artifacts and provenance

## Simulation Exercises
1. Configure branch policies for reviewer and status requirements.
2. Execute a change from ticket creation to approved merge.
3. Produce audit evidence for a selected release.
4. Validate that emergency overrides are logged and reviewable.

## Decision Points
- Which approvals are mandatory by risk category?
- How will exceptions be documented and reviewed?
- What is the evidence retention strategy?

## Success Criteria
- Complete end-to-end traceability for sampled changes
- Clear evidence of separation of duties
- Repeatable, auditable release process
