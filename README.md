# Internship Task 1 - Nmap Scan

## Objective
Scan my local network using Nmap to identify open ports and understand potential security exposures.

## Commands Used
```bash
nmap -sS 192.168.1.0/24 -oN scan.txt
Scan Summary
The scan.txt file contains the raw scan result, including:

IP addresses found on the network

Open ports and associated services

Devices with potentially exposed services

Tools Used
Nmap (TCP SYN scan)

Command Prompt (Windows)

Key Learnings
How to identify open ports

Common services like HTTP (port 80), HTTPS (443), SSH (22)

Basics of network reconnaissance
