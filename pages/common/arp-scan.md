# arp-scan

> Send ARP packets to hosts (specified as IP addresses or hostnames) to scan the local network.
> More information: <https://github.com/royhills/arp-scan>.

- Scan the current local network:

`arp-scan {{[-l|--localnet]}}`

- Scan an IP network with a custom bitmask:

`arp-scan {{192.168.1.1}}/{{24}}`

- Scan an IP network within a custom range:

`arp-scan {{127.0.0.0}}-{{127.0.0.31}}`

- Scan an IP network with a custom net mask:

`arp-scan {{10.0.0.0}}:{{255.255.255.0}}`
