# Environment capture

Reproducibility needs an explicit environment contract rather than a raw dump of the host machine.

Capture dependency locks, container or environment image digests, runtime ABI information, relevant accelerator capabilities, and environment variables that affect scientific behavior.

Record host details separately as provenance so they can help explain divergence without becoming unnecessary hard requirements.

Secrets should never be embedded in the captured environment; record only the required secret or capability name.
