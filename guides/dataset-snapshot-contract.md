# Dataset snapshot contract

A reproducible run needs an immutable dataset identity, not only a human-readable dataset name.

Record the logical dataset name together with a snapshot ID, repository commit, object-store version, or content manifest whose files are cryptographically hashed. If preprocessing changes the bytes consumed by the experiment, version that transformation and record the resulting digest as well.

A mutable URL or `latest` tag is useful provenance but cannot serve as the sole identity.

The snapshot contract should make it possible to prove exactly which bytes entered a run.
