<p align="center">
  <h1 align="center">Capability Emergence in a Tiny RL Sandbox</h1>
  <p align="center"><strong>Measure whether small-model RL in a constrained deduction sandbox produces transferable capability jumps.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Capability Emergence in a Tiny RL Sandbox**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Measure whether small-model RL in a constrained deduction sandbox produces transferable capability jumps.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
