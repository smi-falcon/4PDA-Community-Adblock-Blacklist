# 4PDA Community Blacklist

Ежедневно обновляемый чёрный список доменов рекламы и трекеров для блокировщиков рекламы в форматах Hosts, Adblock/AdGuard, DNSmasq, Unbound, RPZ, Privoxy, DualServer, FQDN, IPv6 и сжатых вариантах.

## Источник

Всеобъемлющий список, который объединяет: AdAway, StevenBlack Unified, NoCoin, nobodysu Android, AppWarden Trackers, SmartTV, YouTube Ads, 1Hosts Lite.

## Ссылки

### Hosts
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_hosts.txt`

### Adblock/AdGuard
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_adblock.txt`

### FQDN
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_fqdn.txt`

### Reduced FQDN
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_reduced_fqdn.txt`

### DNSmasq
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_dnsmasq.txt`

### Unbound
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_unbound.txt`

### RPZ
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_rpz.txt`

### Privoxy
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_privoxy.txt`

### DualServer
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_dualserver.txt`

### IPv6
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_ipv6.txt`

### Compressed
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_compressed.txt`

### IPv6 Compressed
`https://raw.githubusercontent.com/smi-falcon/4PDA-Community-Blacklist/refs/heads/main/Blacklist_ipv6_compressed.txt`

## Структура проекта

```
4PDA-Community-Blacklist/
├── .github/
│   └── workflows/
│       └── update-blacklist.yml
├── scripts/
│   ├── add-header.js
│   └── add-header-and-convert.py
├── Blacklist_adblock.txt
├── Blacklist_hosts.txt
├── Blacklist_fqdn.txt
├── Blacklist_reduced_fqdn.txt
├── Blacklist_dualserver.txt
├── Blacklist_dnsmasq.txt
├── Blacklist_unbound.txt
├── Blacklist_rpz.txt
├── Blacklist_privoxy.txt
├── Blacklist_ipv6.txt
├── Blacklist_compressed.txt
├── Blacklist_ipv6_compressed.txt
├── License.md
└── Readme.md
```

## Инструменты

- `@adguard/hostlist-compiler` v2.1.1
- [Hosts-Conversions](https://github.com/ScriptTiger/Hosts-Conversions)

## Лицензия

MIT