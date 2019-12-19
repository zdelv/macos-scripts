# Mac OS Scripts

Repo for various Mac OS scripts

### flashdevice

Script for flashing a device given a DMG and the block address (dev)
Only images to an APFS drive, cannot create an HFS+ drive.

See --help for more information

```
flashdevice.sh -d PATH --dev PATH [OPTIONS]

Drive flashing utility. Given the path to a DMG and dev path to a drive, flash the drive using ASR.

 Required:
  -d, --dmg         Path to DMG
  --dev, --drive    Path to drive for imaging (/dev/disk2 etc)

 Options:
  -h, --help        Display this help and exit
  -v, --verbose     Enable verbose output
  --noverify        Do not verify before restoring (just run the script)
```
