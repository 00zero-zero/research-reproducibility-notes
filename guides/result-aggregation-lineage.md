# Result aggregation lineage

Every reported aggregate should be traceable to the exact trial results that contributed to it.

Store the aggregation algorithm and version, input result identities, exclusion decisions, weighting rules, and confidence-interval method alongside the aggregate.

Do not copy final means into a report without preserving the trial-level evidence needed to recompute them.

When an input trial is invalidated or replaced, downstream aggregates should receive new identities rather than silently mutating historical results.
