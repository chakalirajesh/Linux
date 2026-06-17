# Package Management in Linux

## Overview

Package management is the process of installing, updating, removing, and managing software on a Linux system.

Ubuntu uses the APT (Advanced Package Tool) package manager.

## Update Package Lists

```bash
sudo apt update
```

This downloads the latest package information from repositories.

## Upgrade Installed Packages

```bash
sudo apt upgrade
```

Updates installed software to newer versions.

## Install a Package

```bash
sudo apt install nginx
```

Example:

```bash
sudo apt install tree
```

## Remove a Package

```bash
sudo apt remove nginx
```

## Search for Packages

```bash
apt search nginx
```

## Package Information

```bash
apt show nginx
```

## List Installed Packages

```bash
apt list --installed
```

## Why Package Management Matters

* Installs required software
* Keeps systems secure
* Updates applications
* Manages dependencies

Package management is a daily task for Linux administrators and DevOps engineers.
