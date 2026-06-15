# Cybersecurity Reconnaissance Tools Assignment

## Nmap

Documentation:
https://nmap.org/docs.html

Description:
Nmap (Network Mapper) is a network scanning tool used to discover hosts, open ports, services, and operating systems on a network.

Command:
nmap -sV sigosec.com

## Whois

Documentation:
https://www.iana.org/help/whois

Description:
Whois is a utility used to retrieve domain registration information and ownership details.

Command:
whois sigosec.com

## Gobuster

Documentation:
https://github.com/OJ/gobuster

Description:
Gobuster is a tool used for directory, DNS, and virtual host enumeration during reconnaissance.

Command:
gobuster dir -u https://sigosec.com -w /usr/share/wordlists/dirb/common.txt
