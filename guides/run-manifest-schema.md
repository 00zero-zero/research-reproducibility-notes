# Run manifest schema

A run manifest should describe the scientific identity of an experiment in a compact, machine-readable form.

Record source revision, method/configuration identity, task and benchmark version, model identity, seeds, immutable input artifact identities, environment or image digest, evaluator identity, and output artifact references.

Separate required reproducibility fields from observed provenance. Requirements determine whether another machine can reproduce the run; observations describe the machine that happened to execute it.

Version the manifest schema itself so readers fail explicitly when they cannot interpret a newer contract.
