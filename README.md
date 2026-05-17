# Sources.List for Debian

Sometimes things break because you've been too rough. Or you might find an empty file when you install Debian offline. So, for anyone in need, here is a suggestion of what the file might look like.

```
# /etc/apt/sources.list for debian 13
# https://github.com/diplomendstadium/debian-etc-apt-sources-list/
deb https://deb.debian.org/debian/ trixie main contrib non-free non-free-firmware
deb https://deb.debian.org/debian/ trixie-updates main contrib non-free non-free-firmware
deb https://security.debian.org/debian-security/ trixie-security main contrib non-free non-free-firmware
deb https://deb.debian.org/debian/ trixie-backports main contrib non-free non-free-firmware
```

For Debian 12, simply replace every instance of 'trixie' with 'bookworm'.
