# syslinux-themes-hamonikr

syslinux theme packages for HamoniKR (BIOS Booting Mode) 


# Developer

Kevin Kim <root@hamonikr.org>


# Installation

## 하모니카 저장소가 없는 경우

```
$ wget -O - http://apt.hamonikr.org/hamonikr.key| sudo apt-key add -
$ sudo bash -c "echo 'deb https://apt.hamonikr.org sun main upstream' > /etc/apt/sources.list.d/hamonikr.list"
$ sudo bash -c "echo 'deb-src https://apt.hamonikr.org sun main upstream' >> /etc/apt/sources.list.d/hamonikr.list"
$ sudo apt update
$ sudo apt install syslinux-themes-hamonikr
```

## 하모니카 저장소가 있는 경우

```
$ sudo apt install syslinux-themes-hamonikr
```


# Issues

https://hamonikr.org/hamoni_board