# Process Management in Linux

## Overview

A process is a running instance of a program. Linux provides several commands to monitor and manage processes.

## What is a Process?

When a program runs, Linux creates a process with a unique Process ID (PID).

## Common Process Commands

### View Running Processes

```bash
ps
```

Detailed View:

```bash
ps -ef
```

### Real-Time Process Monitoring

```bash
top
```

### Enhanced Monitoring

```bash
htop
```

### Find Process ID

```bash
pidof ssh
```

### Search for a Process

```bash
ps -ef | grep nginx
```

## Process States

* Running
* Sleeping
* Stopped
* Zombie

## Why Process Management Matters

DevOps engineers frequently monitor applications, troubleshoot services, and optimize system performance using process management commands.
