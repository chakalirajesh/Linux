# Introduction to Shell Scripting

## What is Shell Scripting?

A shell script is a file containing Linux commands that are executed automatically.

Shell scripting helps automate repetitive tasks and is widely used in DevOps.

## Creating a Shell Script

Create a file:

```bash
nano hello.sh
```

Add:

```bash
#!/bin/bash

echo "Hello, Linux!"
echo "Welcome to Shell Scripting"
```

Make executable:

```bash
chmod +x hello.sh
```

Run:

```bash
./hello.sh
```

## Variables

```bash
#!/bin/bash

name="Rajesh"

echo "Hello $name"
```

## User Input

```bash
#!/bin/bash

echo "Enter your name:"
read name

echo "Welcome $name"
```

## Conditions

```bash
#!/bin/bash

num=10

if [ $num -gt 5 ]
then
    echo "Number is greater than 5"
fi
```

## Loops

```bash
#!/bin/bash

for i in 1 2 3 4 5
do
    echo $i
done
```

## Why Shell Scripting Matters

* Automation
* Server Management
* CI/CD Pipelines
* Monitoring
* Deployment Tasks

Shell scripting is a core skill for DevOps Engineers.
