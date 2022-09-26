# RIPE NCC IPv4 run-out
This repository tracks the current status of IPv4 run-out in the RIPE region.

# Current status
- available prefix sizes (not always on the network bitmask boundary)
  - available blocks of consecutive 1024 addressess: 1
  - available blocks of consecutive 256 addressess: 2
- available (usable) addresses: 1536
- remaining address dust (unusable addresses, smaller than a /24): 0
- count of LIRs: 23670
- count of LIRs with at least one allocation: 22560
- count of LIRs with at least one allocation, without last /22 allocation: 3181
- waiting list stats:
  - LIRs in queue: 992
  - days that first LIR in queue has been waiting: 244

# Notes
The address dust status was moved from `available` to `reserved` on 2019-10-11, as seen in [commit d71f95b](https://github.com/zajdee/ripe-ncc-ipv4-runout/commit/d71f95b1f7c9f639556e395e4ad0f41e54834954).

# Source data
- [delegated-ripencc-extended-latest](https://ftp.ripe.net/pub/stats/ripencc/delegated-ripencc-extended-latest)
- [alloclist.txt](https://ftp.ripe.net/pub/stats/ripencc/membership/alloclist.txt)
- [number-of-lirs](https://labs.ripe.net/statistics/number-of-lirs)
- [waiting-list-stats](https://www.ripe.net/manage-ips-and-asns/ipv4/ipv4-waiting-list) ([json](https://www-static.ripe.net/dynamic/ipv4-waiting-list/stats.json))

Generated at: 2022-09-27 00:30 CEST
