# REFault
A Fault Injection Platform for Rowhammer Research on DDR5 Memory

## Introduction
Welcome to the REFault repository!
This, along with other repositories available at [refault-artifacts](https://github.com/refault-artifacts) provides the resources needed to examine, reproduce, and extend our work. For additional information about REFault, please refer to the accompanying paper.

## Components
REFault consists of

- **Fault Injection Interposer**: The hardware design files of our interposer can be found at [refault-artifacts/fault-injection-interposer](https://github.com/refault-artifacts/fault-injection-interposer).

- **Injection Controller**: The hardware files of our injection controller baseboard can be found at [refault-artifacts/injection-controller](https://github.com/refault-artifacts/injection-controller).

- **Memtest**: Our modified version of [Memtest86+](https://github.com/memtest86plus/memtest86plus) which we used as experiment host software,
can be found at [refault-artifacts/memtest](https://github.com/refault-artifacts/memtest).

- **Control Server**: The scripts and setup instructions for our central control server can be found at [refault-artifacts/injection-controller](https://github.com/refault-artifacts/control-server).
