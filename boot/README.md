This file needed to be modified if you want memory stats  (and mem limits) in your containers

Test it with `docker info`, if you see
```
WARNING: No memory limit support
WARNING: No swap limit support
```
then you need to modify the file.

References:
* https://web.archive.org/web/20170625185736/https://awhitehatter.me/debian-jessie-wdocker/
* https://stackoverflow.com/questions/45541242/docker-stats-shows-zero-memory-usage-even-for-running-containers