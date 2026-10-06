# Linux Fundamentals

**Platform:** TryHackMe – Cyber Security 101  
**Module:** Linux Fundamentals (Parts 1–3)  
**Status:** Completed  

## Overview

Completed hands-on Linux exercises covering command-line navigation, file management, remote access, file transfer, process monitoring, service management, task automation and log analysis.

## Technical Skills Practised

| Area | Commands / Tools | Practical Application |
|---|---|---|
| Linux CLI | `whoami`, `echo`, `ls`, `cd` | User identification, command-line navigation and displaying output |
| File Management | `mkdir`, `mv`, `cp`, `rm`, `cat` | Creating directories, moving, copying, removing and viewing files |
| Text Editing | `nano`, `vim` | Creating and editing files directly from the terminal |
| Remote Access | `ssh` | Connecting remotely to another Linux system |
| User Management | Linux user commands | Working with users and switching between accounts |
| File Transfer | `wget`, `scp` | Downloading and securely transferring files between systems |
| HTTP File Sharing | `python3 -m http.server` | Hosting files for retrieval from another machine |
| Process Monitoring | `ps`, `top` | Identifying running processes and monitoring system activity |
| Service Management | `systemctl` | Starting and managing Linux services |
| Task Automation | `cron` | Understanding scheduled task automation |
| Log Analysis | Apache2 access logs | Reviewing HTTP activity, source IP addresses and requested resources |

## Practical Exercise – Linux File Transfer

As part of the practical lab, I used two Linux systems to demonstrate file hosting and retrieval.

### HTTP Server

I moved a file into the required directory and started a temporary Python HTTP server:

```bash
mv newfile app
cd app
ls
python3 -m http.server
