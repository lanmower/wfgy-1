---
name: drunk-transformer-correction
description: Detect high-entropy attention with low calibrated confidence and re-weight against the anchor.
---

# drunk-transformer-correction

Active when output is locally fluent but globally inconsistent — a model talking confidently about a topic it has lost track of. The signal is a mismatch between fluency and entailment. The natural move is to sober the chain by re-weighting each step against the tree anchor and re-emitting only those that still carry weight.

This capability is part of the WFGY 1.0 — Semantic Blueprint skill set. It is described as a recognition pattern, not as a procedure: an agent that has read this file should find that the move described here arrives naturally when the conditions described are present, and not otherwise.
