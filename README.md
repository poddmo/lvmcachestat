
lvmcachestat displays LVM cache statistics. This repository aims to rework an earlier utility to output in similar format to iostat.

Usage:
```
lvmcachestat VolumeGroup/LogicalVolume
```

History:
- Copyright (C) 2014 Armin Hammer 
- 20141220: hammerar: initial version
- 20161230: rocketraman: Fix core and policy args count
- 20230309: poddmo: rename to lvmcachestat.  Begin to recode the output in the style of iostat
