# 🔒 YACT: Yet Another Cybersecurity Toolbox

This document is a curated collection of open-source security tools aimed at bolstering system security, conducting penetration testing, recovering lost data, and safeguarding online privacy. It offers options for cybersecurity professionals and privacy-conscious users alike, including tools for vulnerability assessment, system defense, network traffic analysis, data recovery, and online privacy protection. Whether you're a beginner or an expert, you'll find tools suited to your needs here. Feel free to explore and incorporate these tools into your digital security toolbox! 🚀🔒

## 📚 Table of Contents

- [🔍 Pentest](#-pentest)
- [🛡️ Protection](#%EF%B8%8F-protection)
- [🧩 Analysis](#-analysis)
- [📦 Hypervisor](#-hypervisor)
- [💾 Data Recovery](#-data-recovery)
- [🔒 Security and Privacy Check](#-security-and-privacy-check)

## 🔍 Pentest


| Tool name       | Quick description                                                                                                                                                                                                                                                                                                                                | Wikipedia                                                        |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| BurpSuite       | Burp Suite can be used for securing or performing penetration testing on web applications. The suite consists of various tools such as a proxy server (Burp Proxy), a web crawler (Burp Spider), an intrusion tool (Burp Intruder), a vulnerability scanner (Burp Scanner), and an HTTP repeater (Burp Repeater).                                | [BurpSuite](https://en.wikipedia.org/wiki/Burp_Suite)            |
| cURL            | cURL (Client URL Request Library) is a command-line interface used to retrieve the content of a resource accessible via a computer network.                                                                                                                                                                                                      | [cURL](https://en.wikipedia.org/wiki/CURL)                       |
| Metasploit      | Metasploit is a project related to computer security. Its goal is to provide information about security vulnerabilities, help with penetration testing, and aid in developing signatures for intrusion detection systems.                                                                                                                        | [Metasploit](https://en.wikipedia.org/wiki/Metasploit)           |
| Nmap            | Nmap is a free port scanner created by Fyodor and distributed by Insecure.org. It is designed to detect open ports, identify hosted services, and gather information about the operating system of a remote computer. Nmap is available for Windows, Mac OS X, Linux, BSD, and Solaris.                                                          | [Nmap](https://en.wikipedia.org/wiki/Nmap)                       |
| Hashcat         | Hashcat is a password recovery tool. It had a proprietary code base until 2015, but was then released as open-source software. Versions are available for Linux, macOS, and Windows. Hashcat supports various hashing algorithms such as LM hashes, MD4, MD5, SHA-family, Unix Crypt formats, as well as algorithms used in MySQL and Cisco PIX. | [Hashcat](https://en.wikipedia.org/wiki/Hashcat)                 |
| John the Ripper | John the Ripper is a free password cracking software tool. Initially developed for Unix operating systems, it now runs on fifteen different platforms. It's used for detecting weak passwords.                                                                                                                                                   | [John the Ripper](https://en.wikipedia.org/wiki/John_the_Ripper) |
| Aircrack-ng     | Aircrack-ng is a suite of tools for assessing WiFi network security. It focuses on different areas of WiFi security, including monitoring, attacking, testing, and cracking.                                                                                                                                                                     | [Aircrack-ng](https://en.wikipedia.org/wiki/Aircrack-ng)         |
| Hydra           | Hydra is a parallelized login cracker which supports numerous protocols to attack. It is very fast and flexible, and new modules are easy to add.                                                                                                                                                                                                | [Hydra](https://en.wikipedia.org/wiki/THC_Hydra)                 |
| Nikto           | Nikto is an open-source web server scanner that performs comprehensive tests against web servers for multiple items, including over 6700 potentially dangerous files/CGIs, checks for outdated versions of over 1250 servers, and version-specific problems on over 270 servers.                                                                 | [Nikto](https://en.wikipedia.org/wiki/Nikto_(software))          |
| SQLmap          | SQLmap is an open-source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over database servers.                                                                                                                                                                                   | [SQLmap](https://en.wikipedia.org/wiki/Sqlmap)                   |
| W3af            | W3af is a Web Application Attack and Audit Framework, an open-source web application security scanner which helps secure web applications by finding and exploiting all web application vulnerabilities.                                                                                                                                         | [W3af](https://en.wikipedia.org/wiki/W3af)                       |

## 🛡️ Protection


| Tool name   | Quick description                                                                                                                                                                                                                                                        | Wikipedia                                                     |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Fail2ban    | Fail2ban is an intrusion prevention framework written in Python. It operates on POSIX systems with a packet control interface (such as TCP Wrapper) or a firewall (such as Netfilter).                                                                                   | [Fail2ban](https://en.wikipedia.org/wiki/Fail2ban)            |
| Nessus      | Nessus is a computer security tool. It reports potential or verified weaknesses on tested machines.                                                                                                                                                                      | [Nessus](https://en.wikipedia.org/wiki/Nessus_(software))     |
| OpenVAS     | OpenVAS (Open Vulnerability Assessment Scanner, formerly GNessUs) is a GNU GPL-licensed fork of the Nessus vulnerability scanner, aiming to enable free tool development as Nessus is now proprietary.                                                                   | [OpenVAS](https://en.wikipedia.org/wiki/OpenVAS)              |
| Snort       | Snort is a free and open-source intrusion detection system (IDS) and intrusion prevention system (IPS) created in 1998 by Martin Roesch.                                                                                                                                 | [Snort](https://en.wikipedia.org/wiki/Snort)                  |
| ClamAV      | ClamAV (Clam AntiVirus) is an antivirus software for UNIX systems. It is mainly used with email servers for email filtering. ClamAV is one of the few antivirus programs available for GNU/Linux and MacOS. It primarily targets viruses attacking Microsoft Windows.    | [ClamAV](https://en.wikipedia.org/wiki/ClamAV)                |
| Netfilter   | Netfilter is a framework that implements a firewall within the Linux kernel starting from version 2.4. It provides hooks within the kernel for the interception and manipulation of network packets during the reception or transmission routines of network interfaces. | [Netfilter](https://en.wikipedia.org/wiki/Netfilter)          |
| iptables    | iptables is a free software in the Linux user space that allows the system administrator to configure the chains and rules in the kernel space firewall (composed of Netfilter modules).                                                                                 | [iptables](https://en.wikipedia.org/wiki/Iptables)            |
| Suricata    | Suricata is a high-performance Network IDS, IPS, and Network Security Monitoring engine. It is open-source and supports multi-threading for better performance.                                                                                                          | [Suricata](https://en.wikipedia.org/wiki/Suricata_(software)) |
| pfSense     | pfSense is an open-source firewall/router computer software distribution based on FreeBSD. It can be installed on physical or virtual machines.                                                                                                                          | [pfSense](https://en.wikipedia.org/wiki/PfSense)              |
| ModSecurity | ModSecurity is an open-source web application firewall (WAF) that works with Apache, IIS, and Nginx. It provides protection from various web-based attacks.                                                                                                              | [ModSecurity](https://en.wikipedia.org/wiki/ModSecurity)      |
| OSSEC       | OSSEC is an open-source, host-based intrusion detection system (HIDS). It performs log analysis, integrity checking, Windows registry monitoring, rootkit detection, time-based alerting, and active response.                                                           | [OSSEC](https://en.wikipedia.org/wiki/OSSEC)                  |

## 🧩 Analysis


| Tool name | Quick description                                                                                                                                                                             | Wikipedia                                            |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| Wireshark | Wireshark is a free and open-source packet analyzer. It is used for network troubleshooting, analysis, software and protocol development, and reverse engineering.                            | [Wireshark](https://en.wikipedia.org/wiki/Wireshark) |
| tcpdump   | tcpdump is a powerful command-line packet analyzer; it allows the user to display TCP, UDP, and other packets being transmitted or received over a network to which the computer is attached. | [tcpdump](https://en.wikipedia.org/wiki/Tcpdump)     |
| Netcat    | Netcat is a computer networking utility for reading from and writing to network connections using the TCP or UDP protocols.                                                                   | [Netcat](https://en.wikipedia.org/wiki/Netcat)       |
| ELK Stack | The ELK Stack consists of Elasticsearch, Logstash, and Kibana. It is used for searching, analyzing, and visualizing log data in real-time.                                                    | [ELK Stack](https://en.wikipedia.org/wiki/ELK_Stack) |

## 📦 Hypervisor


| Tool name  | Quick description                                                                                                                                                                                 | Wikipedia                                              |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| Proxmox VE | Proxmox Virtual Environment is an open-source virtualization solution (AGPLv3 license) based on the Linux KVM hypervisor. It also offers a container solution with LXC and provides paid support. | [Proxmox VE](https://en.wikipedia.org/wiki/Proxmox_VE) |
| VirtualBox | VirtualBox is a free and open-source hosted hypervisor for x86 virtualization. It is developed by Oracle Corporation.                                                                             | [VirtualBox](https://en.wikipedia.org/wiki/VirtualBox) |

## 💾 Data Recovery


| Tool name | Quick description                                                                                                                                                                                                                                                                   | Wikipedia                                          |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| TestDisk  | TestDisk is free and open-source data recovery software designed to recover lost partition data and make non-booting disks bootable again. It can also be used to collect detailed information about a corrupted drive which can then be sent to a technician for further analysis. | [TestDisk](https://en.wikipedia.org/wiki/TestDisk) |
| PhotoRec  | PhotoRec is file data recovery software designed to recover lost files including videos, documents, and archives from hard disks, CD-ROMs, and lost pictures from camera memory.                                                                                                    | [PhotoRec](https://en.wikipedia.org/wiki/PhotoRec) |
| DMDE      | DMDE (DM Disk Editor and Data Recovery Software) is a disk editor and data recovery software with a number of freeware features such as disk editing, simple partition management, and a tool to create disk images and clones.                                                     | [DMDE](https://dmde.com/)                          |

## 🔒 Security and Privacy Check


| Tool name                                                      | Quick description                                                                                                                                                                                                                                                                         | Wikipedia                                                               |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| [https://amiunique.org/](https://amiunique.org/fr/fingerprint) | This website aims at studying the diversity of browser fingerprints and providing developers with data to help them design good defenses. Contribute to the efforts by viewing your own browser fingerprint or consult the current statistics of data provided by users around the world! | [Device_fingerprint](https://en.wikipedia.org/wiki/Device_fingerprint)  |
| [https://haveibeenpwned.com/](https://haveibeenpwned.com/)     | Check if your email address is in a data breach                                                                                                                                                                                                                                           | [Have_I_Been_Pwned](https://en.wikipedia.org/wiki/Have_I_Been_Pwned%3F) |
| Privacy Badger                                                 | Privacy Badger is a browser extension that automatically learns to block invisible trackers. It is developed by the Electronic Frontier Foundation.                                                                                                                                       | [Privacy Badger](https://en.wikipedia.org/wiki/Privacy_Badger)          |
| HTTPS Everywhere                                               | HTTPS Everywhere is a browser extension that ensures you always use HTTPS, protecting your communication from eavesdroppers and man-in-the-middle attacks.                                                                                                                                | [HTTPS Everywhere](https://en.wikipedia.org/wiki/HTTPS_Everywhere)      |
| Disconnect                                                     | Disconnect is a privacy and security extension for your browser that visualizes and blocks third-party trackers.                                                                                                                                                                          | [Disconnect](https://en.wikipedia.org/wiki/Disconnect_(software))       |
| NoScript                                                       | NoScript is a free and open-source extension for Mozilla Firefox, SeaMonkey, and other Mozilla-based web browsers, allowing JavaScript, Java, Flash, and other plugins to be executed only by trusted web sites of your choice.                                                           | [NoScript](https://en.wikipedia.org/wiki/NoScript)                      |
| Ghostery                                                       | Ghostery is a privacy and security-related browser extension and mobile browser application that blocks ads and stops trackers.                                                                                                                                                           | [Ghostery](https://en.wikipedia.org/wiki/Ghostery)                      |
| uBlock Origin                                                  | uBlock Origin is a free and open-source browser extension for content filtering, including ad blocking. It is available for several browsers including Chrome and Firefox.                                                                                                                | [uBlock Origin](https://en.wikipedia.org/wiki/UBlock_Origin)            |
| Digital Defense                                                | Digital Defense is an open-source platform for vulnerability management and threat intelligence. It offers vulnerability scanning, management, and reporting, as well as threat assessment and mitigation.                                                                                | [Digital Defense](https://digital-defense.io/)                          |

## 📄 License
This script is released under the [MIT license](https://github.com/MushuDG/Tools/blob/main/LICENSE).
