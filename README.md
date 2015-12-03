## yotta Target Description using GCC to compile for K22F Devkit

Use this target description to compile [mbed
OS](http://www.mbed.com/en/development/software/mbed-os/) for the [FRDM-K22F
development
board](http://www.mbed.com/en/development/hardware/boards/freescale/frdm_k22f/)
using GCC.

<img src="https://mbed-media.s3.amazonaws.com/frdm-k22f.jpg" width="400">

This target description derives from the generic
[kinetis-k22f-gcc](TBD) target
description, which provides most of the information about how to compile for
the MK22FN512VLH12 chip used on this board.

If you are creating your own board based on the MK22FN512VLH12 chip, you should
copy this target description to use as a starting point, updating the pin
definitions in target.json as necessary.
