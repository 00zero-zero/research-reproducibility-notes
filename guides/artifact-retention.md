# Artifact retention policy

Retention should follow scientific value rather than treating every temporary file equally.

Preserve immutable manifests, configuration, result bundles, evaluator outputs, source identities, and evidence needed to recompute reported claims. Large raw traces can use tiered storage when their digests and lineage remain stable.

Caches, temporary downloads, and rebuildable intermediates can expire aggressively when they are not part of scientific identity.

A deletion policy should never remove the only evidence supporting a published aggregate or claimed reproduction.
