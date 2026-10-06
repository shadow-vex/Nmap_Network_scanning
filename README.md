# Nmap_Network_scanning
# Basic Network Scanning with Nmap

## Project Overview

This project demonstrates a basic network security assessment using
Nmap on an authorized local Windows environment.

The assessment focuses on identifying open TCP ports, discovering
running services, detecting service versions, identifying the operating
system, and performing a basic security analysis of the discovered
services.

---

## Objective

The main objectives of this project are:

- Perform a basic network scan using Nmap.
- Identify open ports on the target system.
- Identify services running on open ports.
- Detect service versions using Nmap.
- Perform operating system detection.
- Analyze the security risks associated with exposed services.
- Document the findings and security recommendations.
- Understand the importance of ethical network scanning.

---

## Tools and Technologies

| Tool | Purpose |
|------|---------|
| Nmap 7.991 | Network discovery and security auditing |
| Windows | Scanning environment |
| PowerShell / Command Prompt | Command execution |
| Virtual Machine / Local Host | Authorized scanning target |

---

## What is Nmap?

Nmap (Network Mapper) is a network discovery and security auditing
tool used to identify hosts, open ports, running services, service
versions, and operating-system information.

It is widely used by network administrators and security professionals
for network visibility and security assessment.

---

## Why Network Scanning Matters

Network scanning helps security professionals understand the attack
surface of a system.

It can help identify:

- Open network ports
- Running services
- Service versions
- Unnecessary network exposure
- Potential areas requiring security review

Identifying unnecessary exposed services can help administrators
reduce the attack surface and improve system security.

---

## Lab Environment

### Scanner

- Operating System: Windows
- Nmap Version: 7.991

### Target

- Target IP: 10.27.217.62
- Operating System: Microsoft Windows 11
- Scan Type: Authorized local network assessment

> **Note:** The target IP should only be used if the system is owned
> by the tester or explicit permission has been provided.

---

# Scanning Methodology

The assessment was performed in multiple stages.

## 1. Nmap Installation Verification

The Nmap installation was verified using:

```powershell
nmap --version
