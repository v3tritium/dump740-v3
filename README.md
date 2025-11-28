dump740 README
===

Dump740 is a UVD decoder for RTLSDR devices.

Installation
---

mkdir build
cd build
cmake ..
make

Running decoder
---
Basic run without any logging:
./dump740

Recommended run with log:
./dump740 |tee -a dump740_$(date '+%Y.%m.%d').txt


Credits and License
---
Forked from https://github.com/SkyRzn/dump740
which were modification of https://github.com/antirez/dump1090

It stays under GNU GPL license.
Please see individual source files for full copyright and license details.

