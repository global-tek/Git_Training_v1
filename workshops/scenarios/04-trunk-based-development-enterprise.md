# Workshop 04 - Trunk-Based Development in Enterprises

## Scenario
A large organization wants faster lead time but has long-lived branches, delayed integration, and frequent merge pain.

## Objective
Adopt trunk-based development safely with enterprise controls.

## Focus Areas
- Short-lived branches and continuous integration into trunk
- Feature flags for incomplete work
- Required checks and quality gates before merge
- Reducing blast radius with incremental delivery

## Simulation Exercises
1. Break a large feature into thin slices merged daily.
2. Use a feature flag to hide partially complete behavior.
3. Enforce branch protection with mandatory checks.
4. Measure integration delay before and after process changes.

## Decision Points
- Which checks should block merges vs. warn only?
- What maximum branch age should be enforced?
- Who owns stale branch cleanup and policy compliance?

## Success Criteria
- Lower merge conflict frequency
- Faster PR cycle time
- Improved deployment confidence with no drop in quality
