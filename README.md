# lib-compress-gzip-c

`gzip` backend (zlib `gz*` API over `libz`) for the `compress` contract.

## Layout

```text
src/                     the .hnl sources
pkg.hnl                  package manifest (deps on compress, libz, libc)
scripts/hnl-gate.sh      the gate
ci.sh                    bupha entry
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

## License

MIT.
