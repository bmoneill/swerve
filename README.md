<div align="center">
    <h1><b>swerve</b></h1>
    <h4>A suckless-inspired Unix-like monolithic kernel for i386 machines.</h4>
</div>

**This is a work in progress. Please don't run this on real hardware.**

## Prerequisites for building

- GNU Binutils cross-compiled for swerve
- GCC cross-compiled for swerve
- GNU Make
- A POSIX shell (`dash`, `bash`, ...)

## Prerequisites for making a GRUB image

- fdisk (from util-linux)
- GNU GRUB

## Building

1. Edit `config.mk` to your liking
2. `make`

## Run in QEMU

1. Run `make run-qemu`

## Build GRUB image

1. Run `make grub-image`

## License

All of the source code for the kernel and libc are licensed under the GNU GPL
v3 (see LICENSE.gpl), unless otherwise noted. All documentation (in the doc
directory) is licensed under the GNU FDL v1.3 (see LICENSE.gfdl), unless
otherwise noted. All videos, images, and audio are licensed under the Creative
Commons Attribution Share-Alike 3.0 Unported License
(<http://creativecommons.org/licenses/by-sa/3.0/>) unless otherwise noted.
