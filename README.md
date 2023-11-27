## Recovery Device Tree for the Samsung Galaxy A03 Core (m168/sp9863a)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a3core-eng
make recoveryimage -j4
```
> Status: unknown // testing phase

---

> Supported Models: SM-A032F, SM-A032M.

> Blobs version:
- Kernel base: A032FXXU4CWI8
- Kernel source: https://github.com/almondnguyen/android_kernel_samsung_a3core
- Ramdisk, DTB, DTBO base: A032FXXU4CWI8

