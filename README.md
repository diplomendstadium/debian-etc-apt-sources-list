# Sources.List for Debian

Sometimes things break because you've played too hard around. Or you have your Debian installed offline and find an empty file from the beginning. So here is a suggestion for everyone in need, what the file might look like.

```
# /etc/apt/sources.list for debian 13
# https://github.com/diplomendstadium/debian-etc-apt-sources-list/
deb https://deb.debian.org/debian/ trixie main contrib non-free non-free-firmware
deb https://deb.debian.org/debian/ trixie-updates main contrib non-free non-free-firmware
deb https://security.debian.org/debian-security/ trixie-security main contrib non-free non-free-firmware
deb https://deb.debian.org/debian/ trixie-backports main contrib non-free non-free-firmware
```
