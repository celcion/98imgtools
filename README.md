# PC98 Image Tools
Tools for working with the PC98 hard drive images used by common emulators.

## Formats Supported
 * HDD
 * HDI
 * NHD
 * SLH

See [`formats`](formats/) for the various format structures.

## Tools
### `hdddump.py`
Display header information from an HDD hard drive image file.

Verifies magic values in header.

### `hddgen.py`
Creates a new blank HDD image file to the user's specifications.

### `hdidump.py`
Display header information from an HDI hard drive image file.

### `nhddump.py`
Display header information from an NHD hard drive image file.

Verifies magic values in header.

### `nhdgen.py`
Creates a new blank NHD image file to the user's specifications.

### `pbr_dump.py`
Tries to identify partitions in a disk image.

### `slhdump.py`
Display header information from an SLH hard drive image file.

Verifies magic values in header.

### `slhgen.py`
Creates a new blank HDD image file to the user's specifications.
