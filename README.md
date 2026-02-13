# CRTM-fix

Binary files used by CRTM in the [GSI](https://github.com/NOAA-EMC/GSI) are **NOT** in [CRTM-fix](https://github.com/NOAA-EMC/CRTM-fix).
Instead, CRTM binary fix files are available from two sources:
- staged in directory `CRTM_BINARY_SOURCE_DIR` on WCOSS2 and select NOAA RHDPCS machines.
  Variable `CRTM_BINARY_SOURCE_DIR` is defined in [GSI](https://github.com/NOAA-EMC/GSI) `modulefiles/gsi_$machine.lua`
  for some, but not all, machines.
- downloadable as a tarball from https://ftp.emc.ncep.noaa.gov/static_files/public/CRTM-fix.

**Note that** these binary files are **Big Endian** and the *TauCoeff* files are **ODPS**. 


## What files are what
The top level directory structure groups the files as follow:

| File/directory            | Purpose |
| --------------            | ------- |
| `README.md`           | This file with basic pointers to more information. |
| `LICENSE.md`          | A copy of the GNU Lesser General Public License, Version 3. |
| `CMakeLists.txt`      | `CMakeLists` file for use with CRTM-fix. |
| `crtm_binary_files.cmake` | List of all CRTM fix files. |

## Disclaimer

The United States Department of Commerce (DOC) GitHub project code is
provided on an "as is" basis and the user assumes responsibility for
its use. DOC has relinquished control of the information and no longer
has responsibility to protect the integrity, confidentiality, or
availability of the information. Any claims against the Department of
Commerce stemming from the use of its GitHub project will be governed
by all applicable Federal law. Any reference to specific commercial
products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by the Department of
Commerce. The Department of Commerce seal and logo, or the seal and
logo of a DOC bureau, shall not be used in any manner to imply
endorsement of any commercial product or activity by DOC or the United
States Government.

