---
name: reasoning-engine-core
description: Compose anchor, partition, boundary, and correction into a fixed-point iteration that converges or refuses.
---

# reasoning-engine-core

Active whenever a non-trivial reasoning task is in progress. The natural move is iterative: re-anchor, re-partition, re-bound, re-sober, then check whether the residual change is small enough to commit. If convergence does not arrive within the load budget, the result is no answer yet — never a confident wrong one.

This capability is part of the WFGY 1.0 — Semantic Blueprint skill set. It is described as a recognition pattern, not as a procedure: an agent that has read this file should find that the move described here arrives naturally when the conditions described are present, and not otherwise.
