<h2 align="center">FREE SCRIPT MULTI XRAY VPN</h2>
<p align="center"><img src="https://img.shields.io/badge/VERSION-V3.0 (LATEST VERSION)-green.svg"></p>
<p align="center"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" height='50'></p><br>
<p align="center"><img src="https://img.shields.io/badge/DEBIAN-9-red.svg"> <img src="https://img.shields.io/badge/DEBIAN-10-red.svg"> <img src="https://img.shields.io/badge/DEBIAN-11-red.svg"><br> <img src="https://img.shields.io/badge/UBUNTU-18.04-blue.svg"> <img src="https://img.shields.io/badge/UBUNTU-20.04-blue.svg"> <img src="https://img.shields.io/badge/UBUNTU-22.04-blue.svg"></p>

![alt text](https://raw.githubusercontent.com/kurosewu/multi/main/pict/IMG_20221021_141336.jpg)

<br>
<h2 align="center">Request IP Before Starting Installation </h2><br>
<p align="center"><b>Contact / Report Any Questions </b>
<br>Facebook
<br><a href="https://fb.com/zan404"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" height='50'> </a>
<br>Messenger
<br><a href="https://m.me/zan404"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/messenger.svg" height='50'> </a>
<br>Telegram
<br><a href="https://t.me/zann404"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/telegram.svg" height='50'> </a>

# OS Supported
* <b>DEBIAN</b>
* `Debian 9` (<b>Stretch</b>) ✓
* `Debian 10` (<b>Buster</b>) ✓
* `Debian 11` (<b>Bullseye</b>) ✓
* <b>UBUNTU</b>
* `Ubuntu 18.04` (<b>Bionic Beaver</b>) ✓
* `Ubuntu 20.04` (<b>Focal Fossa</b>) ✓
* `Ubuntu 22.04` (<b>Jammy Jellyfish</b>)✓

# Support ETC
* `New VPS / Fresh`
* `VPS KVM/XEN Minimum 1GB RAM`
* `HDD Minimum 10GB`
* `Kernel amd64 / generic`
* `Domain From Cloudflare`

# Active Ports
* `Nginx`              : 81
* `Shadowsocks WS`     : 443
* `Shadowsocks GRPC`   : 443
* `Trojan-GFW TCP TLS` : 443
* `Trojan WS/GO TLS`   : 443
* `Trojan GRPC`        : 443
* `Vless WS TLS`       : 443
* `Vless WS NTLS`      : 80
* `Vless GRPC`         : 443
* `Vmess WS TLS`       : 443
* `Vmess WS NTLS`      : 80
* `Vmess GRPC`         : 443

# Commands & Other Features
* Type `menu` to enter features
* Added manual menu for data `backup` & `restore`

# Copy & Paste Script
<b>The First Step</b>
```
apt update -y && apt upgrade -y && apt install -y wget && apt install curl -y && update-grub && reboot
```
<b>Second Step After Rebooting VPS</b>
```
wget -q https://raw.githubusercontent.com/kurosewu/multi/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
<b>Alternative Second Step If Error</b>
```
curl -o setup.sh https://raw.githubusercontent.com/kurosewu/multi/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
<b>Install BBR For Maximum Speed</b>
```
wget -q https://raw.githubusercontent.com/kurosewu/dogter/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh && rm bbr.sh && rm install_bbr.log
```
<b>Alternative To Install BBR If It's An Error</b>
```
curl -o bbr.sh https://raw.githubusercontent.com/kurosewu/dogter/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh && rm bbr.sh && rm install_bbr.log
```
