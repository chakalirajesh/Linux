# Networking Basics for DevOps

## Overview

Networking is one of the most important skills for DevOps Engineers because applications, servers, containers, and cloud services communicate over networks.

## IP Address

An IP Address uniquely identifies a device on a network.

Example:

```text
172.18.89.2
```

Types:

* Public IP
* Private IP

Check your IP:

```bash
ip a
```

## DNS (Domain Name System)

DNS converts domain names into IP addresses.

Example:

```text
google.com → 142.x.x.x
```

Check DNS:

```bash
nslookup google.com
```

## TCP

TCP (Transmission Control Protocol) provides reliable communication.

Features:

* Connection-oriented
* Error checking
* Guaranteed delivery

Examples:

* HTTP
* HTTPS
* SSH

## UDP

UDP (User Datagram Protocol) is faster but does not guarantee delivery.

Examples:

* Video Streaming
* Online Gaming
* DNS Queries

## Why Networking Matters

* Cloud communication
* Kubernetes networking
* Docker networking
* Troubleshooting production systems
* Load balancing and service discovery
