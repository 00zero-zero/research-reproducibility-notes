# External API provenance

Hosted model and tool APIs are external effects whose implementation may change outside the repository.

Record provider, exact model or endpoint identifier, exposed revision, request parameters, normalized input digest, response digest, request ID, timestamp, and usage metadata. Preserve raw responses when policy allows.

If the provider does not offer immutable revisions, state that limitation explicitly and use repeated trials to estimate provider variance.

A seed or stable model name should not be treated as a determinism guarantee unless the provider documents one.
