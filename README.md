# machineid-public

Contains debian package for installation of program `machineid`. This program outputs a fingerprint of the host system.

## Requirements

Currently has support for:
* armhf: A 32-bit ARM architecture (such as Raspberry Pi).
* arm64: A 64-bit ARM architecture used by all Jetson variants (such as Jetson Orin Nano).
* amd64: A 64-bit x86 architecture used by most desktop and server systems (such as Intel and AMD processors).

## Installation

Download package file:
>`wget https://github.com/SynclairVision/machineid-public/raw/main/machineid_1.0.0-1_arm64.deb`

Install:
>`sudo apt-get install ./machineid_1.0.0-1_arm64.deb`

Running:
>`machineid`

Done!
