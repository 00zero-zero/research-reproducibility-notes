# Experiment failure taxonomy

Failure classification should distinguish scientific outcomes from infrastructure problems.

Examples of scientific outcomes include task failure, invalid method action, or exhausted method budget. Infrastructure failures include unavailable models, crashed workers, storage errors, corrupted checkpoints, and transport failures.

Keep the taxonomy typed and versioned so aggregate statistics do not silently mix categories across releases.

The original low-level error and evidence should remain attached to the classified failure for auditability.
