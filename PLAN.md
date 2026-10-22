# Plan: Seed agents coding pipeline test

Maintained by the agents working on `commons-seed-e2e`. Each milestone lists its
acceptance tests; a milestone is done only when its tests pass in CI.

## Milestones

1. Arithmetic module: `calc.py` exposes `add(a, b)` and `multiply(a, b)`;
   `test_calc.py` covers both with unittest.
   Acceptance: `python -m unittest -q` passes.
