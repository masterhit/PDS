### PDS
Planetary Data System (PDS) Raw Image Conversion

Author: WANDECLAYT M./@ceuprofundo

A python script to format raw image files from the Cassini Mission
available in the NASA/JPL Planetary data System:
https://pds-imaging.jpl.nasa.gov/search/

#### 1
Raw image files on PDS carry metadata header and telemetry information that
must be stripped out before the image may be converted.
This script searchs for the image format, bit depth and header/telemetry data
size on the detached header (LBL extension file), remove the non-image data
from the file and reshapes it into a proper raw image file.
