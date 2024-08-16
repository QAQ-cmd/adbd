# Android Debug Bridge Daemon for Linux.

This is a simple adbd for linux, from AOSP.

Based on android-tools.

Cross compile for example:
1. set env
`export PATH=/opt/imx6_4.0/linux-gnueabihf-4.7/bin:$PATH`

2.make
`CC=arm-linux-gnueabihf-gcc STRIP=arm-linux-gnueabihf-strip make`
