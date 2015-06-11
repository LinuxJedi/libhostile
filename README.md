# libhostile

"What if I tossed small pox into a room filled with sprinters after filling their water cups with red bull." - [Brian Aker](https://twitter.com/brianaker/status/301262430116405250)

A lightweight library to be used with `LD_PRELOAD` which will intentially break certain libc calls at various intervals. Specifically designed to cause random failures in network functions and memory allocation.

The tool was originally designed by [Data Differential](http://www.datadifferential.com/) as part of [Gearman](http://gearman.org/) but is now being continued as an independent project maintained by [Andrew Hutchings](https://github.com/LinuxJedi).

Documentation: <http://libhostile.readthedocs.org/>
Travis CI: [![Build Status](https://travis-ci.org/libhostile/libhostile.svg)](https://travis-ci.org/libhostile/libhostile)
