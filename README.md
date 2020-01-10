# dpcmd - CLI tool for SF100/SF600

This is a fork of the [SF100Linux](https://github.com/DediProgSW/SF100Linux) repo from Dediprog.
Because they are not responsive and people have trouble to compile it.

`dpcmd` is a command line tool for Linux to use hardware flashers from [Dediprog](https://www.dediprog.com/). Namely the [SF100](https://www.dediprog.com/product/SF100) and the [SF600](https://www.dediprog.com/product/SF600).

## Building

As dependency you only need `usb.h` which is usually shipped with the libusb-compat library (libusb version 0.1).

```
ArchLinux: libusb-compat
Debian: libusb-dev
Fedora: libusb-devel
openSUSE: libusb-compat-devel
```

Running `make` should give you the `dpcmd` binary.

## License
dpcmd is licensed under the GNU GPLv2.
