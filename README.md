# slock

**slock** configuration by steguiosaur

simple screen locker utility for X.

## Requirements

In order to build slock you need the Xlib header files.

## Installation

Edit `config.mk` to match your local setup (slock is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

```console
make clean install
```

## Running slock

Simply invoke the `slock` command. To get out of it, enter your password.

## Patches

Visit dwm patches at [https://tools.suckless.org/slock/patches/](https://tools.suckless.org/slock/patches/)

```console
patch -p1 < st-patch.diff
```

- `slock-dwmlogoandblurscreen-1.0.diff`
