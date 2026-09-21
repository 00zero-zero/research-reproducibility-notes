# Timeout and budget semantics

Timeouts are part of an experiment when they can change which methods succeed.

Define whether limits apply per operation, decision cycle, trial, or entire run, and specify how retries consume the same budget. Use monotonic clocks for elapsed-time enforcement.

Record timeout events as explicit outcomes rather than collapsing them into generic errors.

When comparing methods, every treatment should receive equivalent budget semantics unless budget policy itself is an experimental variable.
