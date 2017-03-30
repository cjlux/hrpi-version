# hrpi-version

Human-readable Raspberry Pi version

This script helps figuring out what version of a Raspberry Pi board is running.

It extracts the revision and returns it if the `-r` option is given, or returns a human readable string like `rpi-2`.

Hardware revisions are given from [eLinux.org](http://elinux.org/RPi_HardwareHistory).

Since I only care about a few models of the board, the following models are identified: `rpi-zero`, `rpi-2` and `rpi-3`.

## Licence

[MIT](https://raw.githubusercontent.com/damiencaselli/hrpi-version/master/LICENSE.md)
