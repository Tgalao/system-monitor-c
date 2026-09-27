# System Monitor (C)

A command-line system monitor written in C, built to demonstrate systems programming and understanding of how computers work under the hood.

## Example output

```
SYSTEM MONITOR
-----------------------
CPU Usage       32%
RAM Usage       7.8 GB
Disk Usage      421 GB
Processes       184
Uptime          04:32:17
-----------------------
```

## Stack

- C
- Linux system calls / proc filesystem (or platform equivalent)

## Features

- CPU usage
- RAM usage
- Disk usage
- Process count
- System uptime

Possible extensions:
- Real-time monitoring (refreshing display)
- Process list
- Memory breakdown
- Storage breakdown per disk/partition
- Logs
- Alerts (e.g. high CPU/RAM usage)

## What this project demonstrates

C + systems programming + understanding of computers

## Development roadmap

1. Idea
2. Planning
3. Architecture (which system data sources to read, how to structure the code)
4. Development
5. Git / Branches
6. Testing
7. README
8. Screenshots
9. Demo

## Building and running

```bash
gcc -o system_monitor main.c
./system_monitor
```
