A SLEIGH processor spec for [Ghidra](https://github.com/NationalSecurityAgency/ghidra) for the NEC μPD77210 digital signal processor.

## Installation

This repository should be placed within the Ghidra install as the folder `Ghidra/Processors/uPD77016`, such that `Ghidra/Processors/uPD77016/data` is the path to the `data` folder.  Ghidra should automatically add it to the available processor list on its next start, and compile the files when it is first used.

## Manuals

The [μPD77210 Family Digital Signal Processor Architecture manual](https://www.renesas.com/us/en/document/mat/upd77210-family-architecture) covers registers for μPD77210 and μPD77213, but refers to the [μPD77016 Family Digital Signal Processor Instructions manual](https://www.renesas.com/us/en/document/mah/upd77016-family-instructions) for the instruction set, also covering the μPD77015, μPD77016, μPD77017, μPD77018, μPD77018A, μPD77019, μPD77110, μPD77111, μPD77112, μPD77113 and μPD77114. The primary goal of this project is to cover the uPD77210, but it should theoretically be usable for any of these.
