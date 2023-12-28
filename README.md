# FlexZNS-ICCD23-EA

This repository contains the source code of the paper "FlexZNS: Building High-Performance ZNS SSDs with Size-Flexible and Parity-Protected Zones" published in IEEE International Conference on Computer Design (ICCD'23).

The url of the paper is [https://ieeexplore.ieee.org/document/10361036](https://ieeexplore.ieee.org/document/10361036).

If there are any bugs in the code, please contact the me by github issues (English only) or emails (Chinese is OK).

## Warning

This repository is a snapshot of the code used only for the prototype experiments in the paper.

DO NOT use this code in production systems.

## Issues

Due to FEMU's lack of NVMe SGL support and certain NUMA issues, there are performance curve discrepancies in the motivation of the `seq-read` workload. These problems will be addressed and rectified in the upcoming journal release.
