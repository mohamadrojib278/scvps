<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=red&center=true&vCenter=true&lines=Welcome+to+PROJECT+JIBSZZ+[VPN]" alt="JIBSZZ STORE VPN">
</p>

---

<h1 align="center">📡 Project Jibszz VPN</h1>
<p align="center">
  Powerful and secure VPN service with advanced features for all your needs.
</p>

## Docs Index

> [**Docs Index**](#Docs-Index)

> [**About**](#About)

> [**Install**](#Install)

> [**Port Information**](#Port-Information)

> [**Donate**](#Donate)

---

## About

This autoscript is a lifetime free autoscript with simple v2ray x noobzvpns multiport all os features.

---
## Install

``🚀 Installation Guide``
```html
apt update && apt install wget curl screen gnupg openssl perl binutils -y && wget -O install.sh "https://codeberg.org/rojib03/scvps-stable/raw/branch/main/install.sh" && chmod +x install.sh && screen -S fn ./install.sh; if [ $? -ne 0 ]; then rm -f install.sh; fi
```

``If it stops in the middle of the process``
```html
screen -r fn
```
---

## 🌐 Port Information
| **Service**             | **Port(s)**           |
|-------------------------|-----------------------|
| **V2RAY Vmess TLS**      | 443, 2443                  |
| **V2RAY Vmess gRPC**     | 443, 2443                  |
| **V2RAY Vmess None TLS** | 80, 2080, 2082             |
| **V2RAY Vless TLS**      | 443, 2443                  |
| **V2RAY Vless gRPC**     | 443, 2443                  |
| **V2RAY Vless None TLS** | 80, 2080, 2082             |
| **V2RAY Trojan gRPC**    | 443, 2443                  |
| **V2RAY Trojan WS**      | 443, 2443                  |
| **XRAY  ShadowSocks**    | 443, 80                    |
| **XRAY  Socks**          | 443, 80                    |
| **NoobzVPN HTTP**        | 80, 2080, 2082             |
| **NoobzVPN HTTP(S)**     | 443, 2443                  |
| **UDP Custom**           | 443, 2443, 80, 36712, 1-65535                  |
| **SOCKS5**               | 1080, 443, 2443            |
| **SSH WS TLS**           | 443, 2443                  |
| **SSH WS HTTP**          | 80, 2080, 2082             |
| **SLOWDNS**              | 5300, 53                   |

---
## PATH CUSTOM
- vmess websocket
`/whatever & /custom`
`/anypath & /random`

- vless Websocket
`GET /vless HTTP/1.1`
`CONNECT /vless HTTP/1.1`
`CONNECT / HTTP/1.1`

---

## ALPN
---
| Protocol   | Description                |
|------------|----------------------------|
| HTTP/1.1   | Standard HTTP              |
| h2         | HTTP/2 (Multiplexing)      |
---

## OS Support

- Debian 10 -> 12 [ Tested ]
- Ubuntu 20.04 -> 24.04 [ Tested ]
- Kali Linux Rolling [ Tested ]
- Other? [ Soon ]

Detail: Ubuntu. We have tried testing on all LTS and Non LTS versions with code .04 and .10

---

## REST API

[API](./API.md)

---

## BIOT Plugin
- BOT TELEGRAM GUI SCRIPT 
- BOT NOTIFICATION AUTO BACKUP DATABASE

---
