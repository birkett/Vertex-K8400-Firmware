# Velleman K8400 Vertex 3D Printer Firmware
A project to update the vendor provided firmware, against newer versions of Marlin.

This branch only contains documentation - see the other branches for code.

## Branches
### velleman-official
A reverse engineered branch, providing the stock K8400 firmware - based on Marlin 1.0 (1st May 2014). This branch will only be updated if Velleman release firmware beyond v1.4. Official releases are tagged, and available on the releases page, for archiving purposes.

The official firmware reports as Marlin 1.0, Vertex 1.4.
Use Arduino 1.0.6 to compile and upload the official firmware.

### 1.0.x
Contains K8400 firmware, updated against the latest stable Marlin 1.0.x release (currently 1.0.2-1, 15th November 2015).
This branch contains a number of improvements over the stock firmware, but is functionally equivalent, and based on the same Marlin branch as the stock firmware (but newer).

This branch will report as Marlin 1.0, Vertex 1.5.
Use Arduino 1.0.6 to compile and upload the updated firmware.

### 1.1.x
Newest generally available release of Marlin, with the Velleman patches. Actively developed upstream.

Use the latest stable Arduino 1.6.x (currently 1.6.9) to compile and upload.
