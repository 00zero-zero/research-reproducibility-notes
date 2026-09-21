# Trial identity

A scientific trial should have an identity derived from semantic coordinates rather than execution placement.

Useful coordinates include study, treatment, task, repetition, seed lineage, method configuration, and benchmark identity. Worker ID, host name, retry attempt, and wall-clock start time belong in execution provenance instead.

Separating trial identity from attempt identity allows retries and worker reassignment without pretending a new scientific sample was created.

Every result should link both to the stable trial and to the concrete execution attempt that produced it.
