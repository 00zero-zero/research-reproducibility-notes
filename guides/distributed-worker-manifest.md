# Distributed worker manifest

Distributed execution should preserve the same scientific trial identity regardless of which worker runs it.

Record worker placement separately from treatment, task, seed, repetition, and method identity. For each attempt, capture worker ID, hardware capability, start and end time, retry lineage, and artifact locations.

A rescheduled trial should retain its scientific identity while receiving a new infrastructure attempt identity.

This separation makes utilization and failover auditable without changing the experiment definition.
