# REFault
A Fault Injection Platform for Rowhammer Research on DDR5 Memory

## Introduction
Welcome to the REFault repository!
This, along with other repositories available at [refault-artifacts](https://github.com/refault-artifacts), provides the resources needed to examine, reproduce, and extend our work. For additional information about REFault, please refer to the accompanying paper on the [uASC '25 page](https://uasc.cc/).

This work is based on a bachelor's thesis which is available [here](https://files.stefan-gloor.ch/thesis.pdf).

## Components
REFault consists of the following four components:

- **Fault Injection Interposer**: The hardware design files of our interposer can be found at [refault-artifacts/fault-injection-interposer](https://github.com/refault-artifacts/fault-injection-interposer).

- **Injection Controller**: The hardware files of our injection controller baseboard can be found at [refault-artifacts/injection-controller](https://github.com/refault-artifacts/injection-controller).

- **Memtest**: Our modified version of [Memtest86+](https://github.com/memtest86plus/memtest86plus) which we used as experiment host software,
can be found at [refault-artifacts/memtest](https://github.com/refault-artifacts/memtest).

- **Control Server**: The scripts and setup instructions for our central control server can be found at [refault-artifacts/injection-controller](https://github.com/refault-artifacts/control-server).

## How to cite

Please use the following BibTeX entry to cite our work:

```
@inproceedings{refault.uasc25,
  title = {{{REFault}}: {{A Fault Injection Platform}} for {{Rowhammer Research}} on {{DDR5 Memory}}},
  booktitle = {1st {{Microarchitecture Security Conference}} ({{$\mu$ASC}} '25)},
  author = {Gloor, Stefan and Jattke, Patrick and Razavi, Kaveh},
  year = {2025},
  month = feb
}
```
