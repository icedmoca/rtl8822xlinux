# rtl8822xlinux

# Usage

Log in with your favorite distribution, preferably with a new Kernel
```
modprobe -r rtwpci
modprobe -r rtw88
```

You can run `lsmod` to see if they are named somehow differently in your OS,
in case you do not run Debian.

Copy the files from this repo to your system, **change the kernel path as needed**!
Load the modules with `modprobe rtw88` and the WiFi should work.

It is unclear to me whether the `/usr` files are needed or if everything will
work with just the files under `/lib`. Feel free to open an issue about this.
