# Hardware provenance

Hardware should be recorded at the level needed to explain or reproduce behavior.

Capture accelerator model and architecture, relevant memory capacity, precision features, CPU architecture, and driver/runtime versions when they can influence results.

Prefer capability requirements over machine serial numbers. Exact device identity belongs in provenance, while portable capability constraints belong in the reproducibility contract.

When numerical behavior is hardware-sensitive, record that limitation and validate representative hardware classes separately.
