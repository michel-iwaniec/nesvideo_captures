# Rigol DS1104-Z oscilloscope

These directories contain composite captures of the NES PPU pin21 (VOUT).

All data is in .csv format captured from a Rigol DS1104-Z oscilloscope with a compensated probe.

.csv files have been compressed with gzip to use a bit less space.

Python utilities for splitting the .csv.gz files into individual frames and converting them to .png are available here: https://github.com/michel-iwaniec/nesvideo/

## Naming convention

The filenames use suffixes to indicate repeated resets / captures, as follows:
* R0C0 / R1C0 -> Denotes two different captures from two different console resets
* R0C0 / R0C1 -> Denotes two different captures with reset unchanged

If you wish to compare odd / even frames for one particular reset state, make sure to use the same R value.

If you wish to compare different subcarrier phases, you can use all R values.

