# RIPE NCC IPv4 run-out
This repository tracks the current status of IPv4 run-out in the RIPE region.

# Current status
- available prefix sizes (not always on the network bitmask boundary)
  - available blocks of consecutive 1024 addressess: 41
  - available blocks of consecutive 512 addressess: 561
  - available blocks of consecutive 256 addressess: 1566
- available (usable) addresses: 730112
- available (usable) /22-equivalents: 713
- remaining available (usable) addresses not fitting into an /22-equivalent: 0
- remaining address dust (unusable addresses, smaller than a /24): 0
- count of LIRs: 25150
- count of LIRs with at least one allocation: 24753
- count of LIRs with at least one allocation, without last /22 allocation: 2945

# Notes
The address dust status was moved from `available` to `reserved` on 2019-10-11, as seen in [commit d71f95b](https://github.com/zajdee/ripe-ncc-ipv4-runout/commit/d71f95b1f7c9f639556e395e4ad0f41e54834954).

# Source data
- [delegated-ripencc-extended-latest](https://ftp.ripe.net/pub/stats/ripencc/delegated-ripencc-extended-latest)
- [alloclist.txt](https://ftp.ripe.net/pub/stats/ripencc/membership/alloclist.txt)
- [number-of-lirs](https://labs.ripe.net/statistics/number-of-lirs)

Generated at: 2019-10-18 00:30 CEST
