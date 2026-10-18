# lib-compress-gzip-c

gzip backend (zlib `gz*` API over `libz`) for the `compress` contract.

Part of the `handl-lang` org split (ADR-0128). History is a `git subtree
split` of the platform monorepo's `compress-gzip-c/` (via `c`).

## Layout

```text
src/        the .hnl sources
pkg.hnl     dependencies, when any: `{ deps: { <name>: "branch:<ref>" } }`
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```
