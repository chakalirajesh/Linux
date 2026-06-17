# DNS, TCP, UDP and Port Numbers

## DNS Lookup

```bash
nslookup google.com
```

## Test Connectivity

```bash
ping google.com
```

## View Network Interfaces

```bash
ip a
```

## Open Ports

```bash
ss -tuln
```

## HTTP Request

```bash
curl google.com
```

## Common Ports

| Port | Service    |
| ---- | ---------- |
| 22   | SSH        |
| 53   | DNS        |
| 80   | HTTP       |
| 443  | HTTPS      |
| 3306 | MySQL      |
| 5432 | PostgreSQL |

## TCP vs UDP

| Feature     | TCP                 | UDP                    |
| ----------- | ------------------- | ---------------------- |
| Reliability | High                | Low                    |
| Speed       | Moderate            | Fast                   |
| Connection  | Connection-Oriented | Connectionless         |
| Examples    | HTTP, HTTPS, SSH    | DNS, Gaming, Streaming |

## Learning Outcome

* Understand IP addressing
* Learn DNS resolution
* Understand TCP and UDP
* Learn common ports
* Explore Linux networking tools
