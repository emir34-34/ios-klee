# ios-klee

Experimental XNU work for the POCO X8 Pro (`klee`, MediaTek MT6899). **It does not run on the device yet.**

This first commit is an unchanged copy of the kernel patches and CI workflow from
[dipa-studio/ios-sweet](https://github.com/dipa-studio/ios-sweet) at
`45263bee51df4a0f55cdf9c649af886399488ddb` (MIT, see `LICENSE`). Its purpose is to check
that the reference build can be reproduced before anything is changed for klee.

The build uses [blacktop/darwin-xnu-build](https://github.com/blacktop/darwin-xnu-build)
and Apple's open-source releases. This repository holds no Apple firmware, IPSW files,
device backups or device identifiers.
