# SOC Mini Lab – Attack Detection Project

This project demonstrates a simulated cyber attack and how it can be detected using Windows logs and SIEM monitoring.

## Lab Architecture

Attacker Machine: Kali Linux  
Victim Machine: Windows 10  
Monitoring: Sysmon + Wazuh SIEM  

## Tools Used

- Kali Linux
- Windows 10
- Sysmon
- Wazuh
- Nmap
- Hydra

## Attack Scenario

1. Kali machine performs network scan
2. Attacker attempts SMB brute force
3. Windows logs failed login attempts
4. SIEM detects abnormal activity

## Detection

Security Event Logs:

- Event ID 4625 – Failed login
- Event ID 4624 – Successful login

Sysmon Logs:

- Event ID 1 – Process creation
- Event ID 3 – Network connection

## Outcome

Attack detected and investigated successfully.
