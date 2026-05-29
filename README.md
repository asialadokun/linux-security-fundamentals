# Linux security fundamentals 

## Overview 
This project documents my hands-on practical work while learning Linux fundamentals, network inspection, process analysis, permissions, and introductory SOC-style investigations in Kali Linux 

## Skills Practised
* Linux filesystem navigation
* File and directory inspection
* Process monitoring
* Network interface inspection
* Connectivity testing
* Open port investigation
* Log analysis using grep
* Linux permissions
* Basic system investigation


## Commands Used
bash
pwd
ls
ls -la
cd
cat /etc/os-release
ps aux
ip a
ping 8.8.8.8
ss -tulpn
netstat -anp
grep "Failed" auth.log
chmod 732 auth.log


## Screenshots

### Kali Linux Virtual Machine Setup
[Kali VM](screenshots/ss-01-kali-vm.png)

### Linux Navigation
[Navigation](screenshots/ss-02-linux-navigation.png)

### File Inspection and Permissions
[Permissions](screenshots/ss-03-file-permissions.png)

### Process Analysis
[Processes](screenshots/ss-05-process-analysis.png)

### Network Interface Inspection
[Network Interfaces](screenshots/ss-06-network-interfaces.png)

### Open Port Inspection
[Ports](screenshots/ss-08-open-ports.png)

### Log Analysis Using grep
[grep analysis](screenshots/ss-11-grep-log-analysis.png)


## Lessons Learned
* Linux commands provide deep visibility into system activity.
* Process and network inspection are foundational cybersecurity skills.
* Logs are critical for identifying suspicious behaviour.
* grep is extremely useful for filtering authentication events.
* Understanding Linux permissions is important for system security.


## Future Improvements
* Learn shell scripting
* Practice SIEM-style log analysis
* Explore PowerShell logging
* Build more SOC-focused labs
* Simulate incident response scenarios
