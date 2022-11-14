# Manual installation guide v2ray & xray port 443 & 80

## update vps

```bash
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```
## install autoscript
```bash
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/Mrian07/inc/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

## rubah port default ssh 443 ke 4443
```bash
nano /etc/stunnel/stunnel.conf
```
## rubah port v2ray ke 443
```bash
ketik : menu ->[9] ->[3] ->[1]->masukan port 443
```
## rubah port xray ke 443
```bash
ketik : menu ->[9] ->[7] ->[1]->masukan port 443
```
## untuk trojan akan ngikut dari port v2ray/xray
Cek buat akun trojan
```bash
ketik : addtrojan
```
# SELESAI

# ---------------------------------
# Manual installation guide SSH & VPN  (SCRIPT DEFAULT SUDAH PORT 443 UNTUK SSH & VPN)

## update vps

```bash
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

## install autoscript
```bash
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/Mrian07/inc/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
# SELESAI
