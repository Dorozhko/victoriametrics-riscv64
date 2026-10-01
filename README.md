# VictoriaMetrics RISC-V64 Snap

Snap packaging for [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) Single-node for 64-bit RISC-V (`riscv64`) systems.

This repository provides Snap packaging configurations for building VictoriaMetrics for the `linux/riscv64` architecture from the official upstream source.

## Builds

Two Snap base variants are maintained:

| Branch | Snap base | VictoriaMetrics |
|---|---|---|
| `core24` | Ubuntu Core 24 | v1.152.0 |
| `core26` | Ubuntu Core 26 | v1.152.0 |

## Details

- **Architecture:** RISC-V 64-bit (`riscv64`)
- **Operating system:** Linux
- **Package:** VictoriaMetrics Single-node
- **Version:** v1.152.0
- **Snap confinement:** Strict

The VictoriaMetrics source code is downloaded directly from the official upstream repository during the build and is not included in this repository.

## Upstream

[VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)

This repository contains only the Snap packaging and build configuration for RISC-V64.

## License

Apache License 2.0
