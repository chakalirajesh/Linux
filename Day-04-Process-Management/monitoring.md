# Monitoring and Managing Processes

## Viewing Resource Usage

### CPU and Memory Usage

```bash
top
```

### Memory Information

```bash
free -h
```

### Disk Usage

```bash
df -h
```

## Killing Processes

### Kill by PID

```bash
kill PID
```

Example:

```bash
kill 1234
```

### Force Kill

```bash
kill -9 PID
```

### Kill by Name

```bash
pkill process_name
```

## Background Jobs

### Run in Background

```bash
sleep 100 &
```

### View Jobs

```bash
jobs
```

### Bring Job to Foreground

```bash
fg
```

## Learning Outcome

* View running processes
* Monitor CPU and memory usage
* Kill unwanted processes
* Manage background jobs
* Troubleshoot Linux systems
