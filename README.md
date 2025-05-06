# Requirements
- Openwrt Router => configured as (`extender/repeater/wireless bridge mode`)

# ssh/telnet
- Ssh: `ssh root@192.168.1.1`
- Telnet: `telnet 192.168.1.1`

# Install
```
wget -O /etc/nftables.d/ttl64.nft https://raw.githubusercontent.com/afandiazmi/openwrt-ttl-bypass/refs/heads/main/ttl64.nft && fw4 check && /etc/init.d/firewall restart
```
