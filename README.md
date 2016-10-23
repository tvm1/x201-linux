# x201-linux

This is rather minimalist  kernel config for Lenovo Thinkpad X201 that was used to build Linux kernel
on gentoo using `sys-kernel/gentoo-sources-4.4.26:4.4.26`. You can probably use it as a base for other
kernel/distro with `make oldconfig` and bit of tinkering. The configuration is fairly minimalist and is
just enough to get the hardware working. If you need something extra, you will need to enable it on
your own.

## Requirements
- Lenovo X201 laptop
- Ext filesystem on your HDD
- OpenRC or other non-systemd init

## What seems to work
- Wireless (with built-in intel firmware blob - you'll need to `emerge linux-firmware` before compiling).
- Sound
- Ethernet (untested)
- Bluetooth (untested)
- Power management junk

Enjoy!
