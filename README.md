VictoriaMetrics RISC-V64 Snap

A Snap package of VictoriaMetrics Single-node built specifically for 64-bit RISC-V (riscv64) systems.

This project provides an easy way to deploy VictoriaMetrics on RISC-V64 Linux devices and servers using the Snap package format.

About

The package is based on the official VictoriaMetrics v1.152.0 source code and is built for the linux/riscv64 architecture.

The build is performed using Snapcraft and Launchpad remote builds. The official VictoriaMetrics source is downloaded automatically during the build process, so the upstream source code is not included in this repository.

Target platform

* Architecture: RISC-V 64-bit (riscv64)
* Operating system: Linux
* VictoriaMetrics: v1.152.0
* Snap base: Ubuntu Core 24 (core24)
* Snap confinement: Strict

Why this project?

Official pre-built VictoriaMetrics packages are primarily distributed for commonly used architectures such as AMD64 and ARM64. This project provides a Snap packaging solution specifically for RISC-V64, making VictoriaMetrics easier to deploy on RISC-V hardware.

It can be useful for:

* RISC-V single-board computers
* RISC-V development platforms
* RISC-V servers
* IoT and edge systems
* Monitoring and time-series data collection on RISC-V infrastructure

Build

The package can be built remotely for RISC-V64 using Snapcraft:

snapcraft remote-build --build-for=riscv64

The resulting package is:

victoriametrics-riscv64_1.152.0_riscv64.snap

Repository

This repository contains only the Snap packaging configuration and documentation. The VictoriaMetrics source code remains in the official upstream repository.

Upstream project: VictoriaMetrics
Upstream source: https://github.com/VictoriaMetrics/VictoriaMetrics

License

VictoriaMetrics is licensed under the Apache License 2.0.
