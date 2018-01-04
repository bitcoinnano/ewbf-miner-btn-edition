# ewbf-miner-btn-edition
bitcoin gold cuda miner

Download Windows BTN Cuda Miner
Download Linux BTN Cuda Miner
Writen for pascal gpus but works on cards with at least 1Gb memory, and Compute Capability 3 and higher. Miner contain dev fee 2%.

History: Version 0.3.2b - BTN

Added support for Bitcoin Gold
Version 0.3.2b Increased speed up to 2%, depends on card model. some cards not give any speed changes. Reduced gpu memory usage. Improved stability.

Version 0.3.1b Increased speed up to 4%, depends on card model. some cards not give any speed changes. Minor optimizations.

Version 0.3.0b

Integrated nvml (NVIDIA Management Library) for temperature monitoring.
Added option --templimit for set max gpu temperature.
Added option --logfile for custom file name.
Added option --api simple json based api.
Option --solver now allow you to set solvers for different devices.
Optimizations up to 2% depends on cards.
See file Help.txt for more detailed help.
Version 0.2.0b

Added three additional solvers.
Added benchmark which test each solver on miner start and select fastest for each card.
Added option --solver to manual solver selection.
Added option --eexit to exit when the miner fails, it will allow you to use a script to automatically restart or perform other actions
Added option --log logging to a file.
Minor optimizations of solvers and working loop as a result 1 - 4% speed increase depends on card model.
Thanks to new solvers now this version must work with old gpus better.
For more info about new options see help -h for short explanation and examples.
Version 0.1.0b Speed increase 2 - 5% For old cards compute capabilities 2.x 3.x try version 0.0.6b it can be faster.

Version 0.0.9b

Speed increase to 10%.
NOTE this version can be unstable.
For old cards compute capabilities 2.x 3.x try version 0.0.6b it can be faster.
Version 0.0.8b

"Cosmetic" optimizations of solver. Increased speed around 2%
Reduced amount of rejected shares.
New dynamic intensity system.
Version 0.0.7b

Performance improvements. Old cards may be slower than with version 0.0.6b.
I wanted release it as fast as possible. So new solver can be less stable.
Version 0.0.6b

For some older cards performance improvements up to 10%
Bug fixes
Version 0.0.5b

Speed improvement up to 20%
Fixed stratum compatibility (works better with many pools)
Fixed 1Gb card bug
Added statistic (counter of shares and ping)
Version 0.0.4b

Completely new watchdog system.
Fixed a bug in the solver
Binary linux version compiled and tested in debian.
