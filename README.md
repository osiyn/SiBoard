# SiBoard

### Start GOWIN IDE on Linux(Ubuntu-24.04)
need to uninstall ```libfreetype.so.6``` to ide work on Ubuntu
```bash
$ rm ~/Progs/Gowin_V1.9.11.03_Education_Linux/IDE/lib/libfreetype.so.6
```
than export path to libs and run binary
```bash
$ export LD_LIBRARY_PATH=~/Progs/Gowin_V1.9.11.03_Education_Linux/IDE/lib
$ ./Progs/Gowin_V1.9.11.03_Education_Linux/IDE/bin/gw_ide
```
