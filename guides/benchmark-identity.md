# Benchmark identity

A benchmark is more than a dataset.

Its identity should include task construction, environment wrapper, action and observation schema, reset rules, limits, allowed tools, scorer implementation, aggregation logic, and exclusions. Dataset identity should be a dependency of this contract rather than a substitute for it.

When any of these semantics change, the benchmark version or digest should change even if the examples remain byte-identical.

This makes score comparisons auditable across releases.
