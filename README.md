# Config for tornblue that builds using GH actions

Use this repository to update the tornblue keymap/config and download the firmware from GH actions workflow output, then flash like any other zmk firmware. 

`.github/workflows/build.yml` points to `PanKnst/zmk` which is forked from `rtitmuss/zmk` but rebased on `zmkfirmware/zmk` so basically takes advantage of `zmkfirmware/zmk`'s GH actions setup to build using west but includes the `tornblue` keyboard from `rtitmuss/zmk`. Some minor changes were made in the `PanKnst/zmk` fork to get the build to work but these can be seen in commits there. 
