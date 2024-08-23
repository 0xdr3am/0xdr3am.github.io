
# HackTheBox - Machine Name

## Machine Information
- OS: Windows/Linux
- IP: 10.10.10.10
- Difficulty: Easy/Medium/Hard

## Enumeration
- Ran Nmap scan and discovered open ports/services:
```
nmap -p- -sV 10.10.10.10
```
- Enumerated the web server and found a login page at `http://10.10.10.10/login`

## Exploitation
- Identified a potential vulnerability in the login page.
- Exploited the vulnerability using a SQL injection attack to bypass authentication and gain access to the admin panel.

## Privilege Escalation
- Found a vulnerable service running with root/admin privileges.
- Exploited the vulnerability to escalate privileges and gain root/admin access.

## Post-Exploitation
- Gathered sensitive information from the compromised machine.
- Explored the file system and discovered interesting files and directories.
- Extracted credentials and other valuable data.

## Conclusion
- Successfully compromised the machine and achieved the objectives.
- Documented the steps taken and findings for future reference.
