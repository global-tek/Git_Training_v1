# Workshop 06 - Incident Response and Hotfix Flow

## Scenario
A production incident requires immediate remediation while feature work continues.

## Objective
Apply a controlled hotfix workflow that balances speed, stability, and traceability.

## Focus Areas
- Hotfix branch creation from production state
- Risk-based review and accelerated approval lanes
- Forward-merging fixes to active development branches
- Post-incident documentation and process improvement

## Simulation Exercises
1. Create a hotfix branch from the latest production tag.
2. Implement and validate a minimal corrective change.
3. Merge the fix into production and propagate it to trunk.
4. Produce a postmortem summary with SCM evidence.

## Decision Points
- What criteria activate emergency change mode?
- Which tests are mandatory even in fast-track conditions?
- How are communication and ownership handled during incident windows?

## Success Criteria
- Reduced mean time to recovery
- No orphaned fixes or branch divergence after incident closure
- Strong audit record for incident timeline and approvals
