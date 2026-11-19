# WhatIsMyIPNow

Free IP, DNS and network tools at **[whatismyipnow.com](https://whatismyipnow.com)**:
find your IP, check DNS and email records, test VPN leaks. No sign-up.

## Your IP from a terminal

```sh
curl ip.whatismyipnow.com        # IPv4 or IPv6, whichever your connection uses
curl ipv4.whatismyipnow.com      # IPv4 only
curl ipv6.whatismyipnow.com      # IPv6 only
curl ip.whatismyipnow.com/json   # {"ip":"…"}
```

Plain text ending with a newline, no API key. Limit: 300 requests per 5 minutes per IP.

## On the site

- **IP and networking:** your IP, ISP and location, IP and ASN lookup, WHOIS, subnet calculators, port checker, ping, traceroute, speed test
- **DNS and email:** DNS lookup and propagation, MX, SPF, DMARC and DKIM checks, email header analyzer
- **Privacy and security:** WebRTC leak test, proxy and VPN check, browser fingerprint, SSL and HTTP headers
