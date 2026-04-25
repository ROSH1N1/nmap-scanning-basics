# Nmap Scanning Basics

## What is Nmap?

Nmap (Network Mapper) is a tool used to scan networks and discover open ports, services, and hosts.

It helps in identifying possible entry points for attackers.

---

## Common Commands

### 1. Basic Scan
nmap <target>

- Scans top ports of the target

---

### 2. Service Version Detection
nmap -sV <target>

- Shows which services are running (like HTTP, SSH)
- Displays version information

---

### 3. Aggressive Scan
nmap -A <target>

- Enables OS detection
- Detects services and versions
- Runs default scripts

---

## Example Scan

Command:
nmap -sV 192.168.1.1

Output (example):
- Port 22 → Open (SSH)
- Port 80 → Open (HTTP)

---

## What I Learned

- How to identify open ports
- How to detect running services
- How attackers find entry points in a system
