# Wonderland

Writeup for [Wonderland](https://tryhackme.com/room/wonderland) room at [TryHackme](https://Tryhackme.com).

Table of Contents
=================
* [Port Scan](#Port-Scan)
* [Webpage](#Webpage)
* [Directory Enumeration](#Directory-Enumeration)
* [SSH Bruteforce](#SSH-Bruteforce)
* [Python Library Exploit](#Python-Library-Exploit)
* [Privillege Escalation](#Privillege-Escalation)
* [Conclusion](#Conclusion)

# Port Scan

Issuing port scan with `nmap` showed 3 open ports -  ***ssh*** and ***http***.

# Nmap 7.92 scan initiated Wed Feb nmap -A -T4 -v 10.10.108.167

