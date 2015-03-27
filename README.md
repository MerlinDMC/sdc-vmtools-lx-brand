# SmartOS lx-brand VM Guest Tools

The VM Guest tools contains scripts that are used to create SmartOS lx-brand images.


## Installing

To install the guest tools, run the ./install.sh script with the -i flag specifying the install path:

    ./install.sh -i /data/chroot


## What Gets Installed

The `install.sh` script installs the following:

- rc.local boot scripts from `src/lib/smartdc`
- Symlinks to binaries found in `/native`. See `symlinks.txt` for the list of relevant binaries
- Wrapper scripts for binaries in `/native`. See `wrappers.txt` for the list of relevant binaries
