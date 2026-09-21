# Evaluator determinism

An experiment is not reproducible if its evaluator can change independently of the method being tested.

Freeze the scorer implementation, configuration, normalization rules, thresholds, aggregation logic, and any model-based judge identity. Record evaluator randomness separately from method randomness.

When an evaluator calls an external model API, preserve request and response evidence so later audits can distinguish method variance from judge variance.

A metric should be recomputable from immutable trial outputs and a versioned evaluator contract.
