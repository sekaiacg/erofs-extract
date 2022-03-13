**extract.erofs**

****
**调用erofs-utils实现的提取erofs镜像的工具**

**使用c语言编写，可能有未知的bug......**

**提取包含：**
- fs_config
- files_context

****
**The utility that calls the erofs-utils implementation to extract the EROFS image**

**Written in C language, may have unknown bugs......**

**Extract contains:**
- fs_config
- files_context

****
**fs_config:**`vendor/app 0 2000 0755`

**files_context:** `vendor/bin/hw/android.hardware.bluetooth@1.0-service-qti 1002 1002 0755 capabilities=0x1000`

```
usage: [options]

  Extract files from image:
  -h, --help             Help info
  -i, --image=[FILE]     Image file
  -p                     Print all entrys
  --print=X              Print the target of path X
  -x                     Extract all entries
  --extract=X            Extract the target of path X
  --extract-conf=[FILE]  Extract the target of config
  -r                     When using config, recurse directories
  --only-cfg-and-ctx     Only Extract fs_config and files_context
  -T#                    [1-16] Use # threads
  -f, --overwrite        [default: skip] overwrite files that already exist
  -o, --outdir=X         Output dir
  -V, --version          Print the version info
```
