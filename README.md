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
**fs_config:**`vendor/bin/hw/android.hardware.bluetooth@1.0-service-qti 1002 1002 0755 capabilities=0x1000`

**files_context:** `/vendor/bin/hw/android\.hardware\.bluetooth@1\.0-service-qti u:object_r:hal_bluetooth_default_exec:s0`

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
  --only-cfg-and-ctx     Only extract fs_config and files_context
  -T#                    [1-X] Use # threads, -T0: X/2
  -f, --overwrite        [default: skip] overwrite files that already exist
  -o, --outdir=X         Output dir
  -V, --version          Print the version info
```

**贡献者/contributors**
- 感谢[lateautumn233](https://github.com/lateautumn233)提供的[erofs-utils](https://github.com/lateautumn233/erofs-utils)编译方法
- Thanks to [lateautumn233](https://github.com/lateautumn233) for the [erofs-utils](https://github.com/lateautumn233/erofs-utils) compilation method.
