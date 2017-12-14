# Claymore-s-Dual-Ethereum-Decred_Siacoin_Lbry_Pascal-AMD-NVIDIA-GPU-Miner-v10.2
Claymore's Dual Ethereum + Decred/Siacoin/Lbry/Pascal AMD+NVIDIA GPU Miner.

=========================

Latest version is v10.2:

- fixed critical issues in remote management feature (attacker could crash miner even in read-only mode).
- now miner supports up to #299 epoch.
- in rare cases ADL API calls can hang, now watchdog checks it as well.
- improved "-minspeed" option, check readme for details.
- added "miner_getstat2" command to remote management, check "API.txt" for details.
- EthMan: added detailed stats mode in main window.
- a few minor improvements in both miner and EthMan.


LINKS:

MEGA: https://mega.nz/#F!puIlHRZQ!orYNqW3SLn555xF2fwTjgQ


TESTED NVIDIA DRIVERS (other versions are untested, they can be worse or better):
9xx cards in Windows 7 x64: just use latest/recent drivers from Nvidia website (for example, 368.81). Note that latest 372.54 is slower than 368.81.
9xx cards in Windows 10 x64: you have to use old drivers (for example, 352.xx) and miner built for cuda6.5. 
10xx cards in Windows 7 x64: just use latest 372.54 drivers from Nvidia website.
10xx cards in Windows 10 x64: just use latest 372.54 drivers from Nvidia website, note that you must have Win10 Anniversary update.
