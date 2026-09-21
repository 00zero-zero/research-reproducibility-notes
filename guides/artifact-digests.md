# Artifact digests

Mutable names are convenient for humans but insufficient for reproducibility.

Important inputs and outputs should resolve to immutable content identities such as cryptographic digests, repository commits, object-store version IDs, or Merkle roots. The manifest can retain a readable logical name while also storing the immutable identity actually consumed.

Prioritize source bundles, datasets, prompts, model weights, lockfiles, benchmark definitions, evaluator configuration, and final result bundles.

Transient caches and scratch files usually need provenance, not scientific identity.
