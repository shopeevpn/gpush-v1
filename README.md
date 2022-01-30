# boss-v3
```
https://raw.githubusercontent.com/shopeevpn/v3-boss/main/
```

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils -y && wget -P /root -N --no-check-certificate https://raw.githubusercontent.com/shopeevpn/boss-v3/main/setup.sh && chmod +x setup.sh && "/root/setup.sh"
```
