# Linux Instant Boot
Research project at CECA, Peking University.

# Main Idea
* Use RAM-Disk
* Only include essential drivers and modules
* Use X.org as X11 server
* Linux Kernel parameter is set to "quiet", but not used (Use U-Boot params instead)
* Have basic network functions (inter-process sockets) for X11

# Config Files
These configureation files are compatiable with buildroot's pre-defined cubieboard configs, using 'legacy' sunxi u-boot and kernel.

I am trying to build a kernel from scratch using sunxi kernel and mainstream u-boot, hoping to get better boot time result. The result will be put at another branch.
