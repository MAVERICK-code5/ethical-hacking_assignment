# Ethical Hacking Lab Project

## Overview

This repository contains practical exercises covering Linux, networking, scripting, secure coding, and web security. The project demonstrates core ethical hacking concepts through hands-on tasks and implementations.

---

## Project Structure

```
.
├── section1_commands.txt
├── port_report.sh
├── password_checker.py
├── network_scanner.py
├── section3_networking.docx
├── pointer_basics.c
├── buffer_test.c
├── c_port_scanner.c
├── section5_nmap.docx
├── http-server-info.nse
├── section6_xss.pdf
├── keylogger.html
└── README.md
```

---

## Section 1: Linux and Bash

* Collection of essential Linux commands
* Bash script for port scanning
* Automates scanning of common ports and saves results

---

## Section 2: Python Security Tools

### Password Checker

* Evaluates password strength
* Checks length, uppercase, lowercase, numbers, and special characters
* Provides improvement suggestions

### Network Scanner

* Takes target IP and port list as input
* Scans ports using sockets
* Displays OPEN or CLOSED status
* Saves results and shows scan duration

---

## Section 3: Networking Concepts

Covers:

* OSI model and its 7 layers
* Public and private IP addressing
* Common ports and services
* Differences between TCP and UDP
* Network Address Translation (NAT)

---

## Section 4: C Programming and Security

### Pointer Basics

* Demonstrates pointer usage and memory access

### Buffer Overflow Program

* Uses unsafe strcpy function
* Demonstrates buffer overflow vulnerability
* Includes explanation, risks, and fixes

### Port Scanner in C

* Uses sockets to scan ports
* Identifies open and closed ports on localhost

---

## Section 5: Nmap Scanning

### Scans Performed

* Ping scan
* TCP SYN scan
* Service version detection
* OS detection
* Default NSE script scan

### Custom NSE Script

* http-server-info.nse
* Extracts HTTP status code, server header, and page title

---

## Section 6: Web Security (XSS)

### XSS Testing

* Tested multiple payloads including script, image, and SVG
* Demonstrates alert execution, cookie access, and DOM manipulation

### Keylogger Demo

* Captures keystrokes using JavaScript
* Displays input on the page
* Demonstrates risks of client-side attacks

---

## How to Run

### Bash Script

```
chmod +x port_report.sh
./port_report.sh <target_ip>
```

### Python Scripts

```
python3 password_checker.py
python3 network_scanner.py
```

### C Programs

```
gcc file.c -o output
./output
```

### Nmap Script

```
nmap --script=./http-server-info.nse scanme.nmap.org
```

### HTML Demo

Open keylogger.html in a web browser

---

## Security Concepts Learned

* Buffer overflow vulnerabilities
* Input validation and secure coding
* Cross-site scripting (XSS)
* Network scanning and reconnaissance
* Basic exploitation techniques
  
Name : Omkar S
