# Users and Groups in Linux

## Overview

Linux is a multi-user operating system. Multiple users can access the same system while maintaining security and isolation.

## User Types

### Root User

* Has complete control over the system.
* User ID (UID) = 0.

### Regular User

* Limited permissions.
* Used for daily tasks.

### System User

* Created by applications and services.

## Useful Commands

### Current User

```bash
whoami
```

### User Information

```bash
id
```

### List Logged-in Users

```bash
who
```

### User Account Details

```bash
cat /etc/passwd
```

## Groups

Groups help manage permissions for multiple users.

### View Groups

```bash
groups
```

### View Group Information

```bash
cat /etc/group
```

## Why Users and Groups Matter

* Improves security
* Controls access to files
* Simplifies administration
* Essential for server management
