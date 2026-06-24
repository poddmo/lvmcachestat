
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

Cache measurement references:
- https://www.kernel.org/doc/Documentation/device-mapper/cache.txt
- https://en.wikipedia.org/wiki/Cache_performance_measurement_and_metric
- https://oneuptime.com/blog/post/2026-03-04-monitor-cache-hit-ratios-performance-rhel-9/view#what-good-numbers-look-like
