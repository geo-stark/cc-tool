# cc-tool
Texas Instruments CC Debugger flash tool

# 
This is the original cc-tool hosted previously on sourceforge (http://sourceforge.net/projects/cctool/).
I (the author) currently have no plans to evolve it somehow although I'm ready to maintain it if needed

## Building from source, dependencies:
Ubuntu: libusb-1.0-0-dev, libboost-all-dev, autoconf, libtool
Fedora: boost-devel, libusb1-devel, libtool, autoconf
Mac OS 10.6.7, from ports: libusb boost pkgconfig

## User guide:
 man cc-tool

### Additional:
File udev/90-cc-debugger.rules cotains udev rules changing permissions 
for TI CC Debugger device and TI evolution boards so they can be used 
from non-privileged accounts. Copy it to /etc/udev/rules.d

### Bug reports:
If you found a bug try to reproduce it with command line option --log and
send the log file along with problem description to george-u@yandex.com
