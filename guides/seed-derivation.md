# Deterministic seed derivation

Distributed experiments should derive seeds from semantic coordinates rather than worker scheduling.

Start from one root seed and derive child seeds from stable fields such as experiment, treatment, task, repetition, and RNG stream name. A cryptographic hash or counter-based generator can turn those coordinates into fixed-width seeds.

Keep model sampling, environment randomness, augmentation, and search in separate streams. This prevents accidental correlation and makes retries independent of which worker executes them.

Record both the root seed and the derivation algorithm version.
