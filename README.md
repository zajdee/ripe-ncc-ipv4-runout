# RIPE NCC IPv4 run-out
This repository tracks the current status of IPv4 run-out in the RIPE region.

# Current status
- available prefix sizes (not always on the network bitmask boundary)
- available (usable) addresses: 0
- remaining address dust (unusable addresses, smaller than a /24): 0
- count of LIRs: 23501
- count of LIRs with at least one allocation: 22689
- count of LIRs with at least one allocation, without last /22 allocation: 3027
- waiting list stats:
  - LIRs in queue: 555
  - days that first LIR in queue has been waiting: 72

# Notes
The address dust status was moved from `available` to `reserved` on 2019-10-11, as seen in [commit d71f95b](https://github.com/zajdee/ripe-ncc-ipv4-runout/commit/d71f95b1f7c9f639556e395e4ad0f41e54834954).

# Source data
- [delegated-ripencc-extended-latest](https://ftp.ripe.net/pub/stats/ripencc/delegated-ripencc-extended-latest)
- [alloclist.txt](https://ftp.ripe.net/pub/stats/ripencc/membership/alloclist.txt)
- [number-of-lirs](https://labs.ripe.net/statistics/number-of-lirs)
- [waiting-list-stats](https://www.ripe.net/manage-ips-and-asns/ipv4/ipv4-waiting-list) ([json](https://www-static.ripe.net/dynamic/ipv4-waiting-list/stats.json))

Generated at: 2022-02-19 00:30 CET
