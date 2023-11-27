---
description: Clash 的 DNS 支持类型
---

# DNS 支持类型

## UDP

```yaml
- 114.114.114.114
```

## DNS over TLS

```yaml
- tls://1.1.1.1
```

## DNS over HTTPS

```yaml
- https://doh.pub/dns-query
```

## DNS over HTTP/3

```yaml
- https://dns.alidns.com/dns-query#h3=true
```

## DNS over QUIC

```yaml
- quic://dns.adguard.com:784
```

## system

```yaml
- system://
- system
```

## dhcp

```yaml
- dhcp://en0 # dns from dhcp
```