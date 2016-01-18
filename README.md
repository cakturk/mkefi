mkefi
=====

Legacy to UEFI ISO Converter


Usage:
------

```

Usage : ./mkefi [-h] [-v] --cdlabel LABEL --input LEGACY_ISO --output EFI_ISO
                     [-m TITLE] [-s TITLE]

    mandatory arguments:
     -l, --cdlabel       set volume name to cdlabel
     -i, --input         path to legacy ISO file
     -o, --output        put new UEFI ISO into this file

    optional arguments
     -m, --mentry        set default grub menuentry title
     -s, --mentrysafe    set safe-mode grub menuentry title
     -h, --help          display this message and exit
     -v, --version       display script version
```
