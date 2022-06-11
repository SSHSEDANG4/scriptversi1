# SSN SCRIPT VPS SCRIPT 1.0 (INSTRUCTION)
- Auto Scripti Install Vps Pertalite, Telegram : t.me/sshsedang

# If Not User Root
```shell
apt install wget && wget https://raw.githubusercontent.com/SSHSEDANG4/simple-root-vps/main/root-main/root.sh && chmod +x root.sh && ./root.sh
```

# Update 
```shell
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```
# Installation
```shell
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils -y && wget -P /root -N --no-check-certificate https://raw.githubusercontent.com/Jagoanneon25/Autoscript/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
# Feature
1. SSH  <br>
2. CDN CLOUDFLARE <br>
3. XRAY <br>
4. V2RAY <br>
5. SQUID PROXY <br>
6. TROJAN GFW <br>
7. OPENVPN
8. AUTO DELETE EXPIRATE ACCOUNT <br>
9. BACKUP DATA <br>
10. AUTO REBOOT GMT +5 <br>

# OS SUPPORT
- Debian 10 <br>
- Ubuntu 18-20
