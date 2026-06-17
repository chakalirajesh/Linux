# Linux Permissions

## Overview

Permissions determine who can read, write, and execute files.

## Permission Types

| Symbol | Meaning |
| ------ | ------- |
| r      | Read    |
| w      | Write   |
| x      | Execute |

## View Permissions

```bash
ls -l
```

Example:

```text
-rw-r--r-- 1 rajesh rajesh file.txt
```

## Change Permissions

### Add Execute Permission

```bash
chmod +x script.sh
```

### Numeric Permissions

```bash
chmod 755 script.sh
```

Meaning:

* 7 = rwx
* 5 = r-x
* 5 = r-x

## Change Ownership

```bash
sudo chown user:user file.txt
```

## Practical Examples

```bash
touch script.sh

chmod +x script.sh

ls -l
```

## Learning Outcome

* Understand Linux users
* Understand groups
* Read file permissions
* Modify permissions using chmod
* Change ownership using chown
