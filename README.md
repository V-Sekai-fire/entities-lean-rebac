# entities-lean-rebac

A Lean 4 relationship-based access-control core: a dependency-free authorization core with its proofs, and a research tier that uses Mathlib.

## What it is for

`NoGod` is the production core and needs no Mathlib; the `ReBAC` research proofs do. The ports are narrow query contracts, and nothing here reaches concrete I/O.

## Build

```sh
lake build Rebac
lake build Research
```

The first is the gate. The research tier does not gate and may fail.

## Licence

MIT; see `LICENSE`.
