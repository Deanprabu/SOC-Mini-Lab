# Attack Simulation

This step demonstrates how the attack was simulated from the attacker machine.

## Step 1 – Network Scan

From Kali Linux:

nmap -sS 192.168.56.102

This command scans the victim machine for open ports.

## Step 2 – SMB Brute Force

hydra -l administrator -P passwords.txt smb://192.168.56.102

The attacker attempts multiple password guesses against the SMB service.

## Result

Multiple authentication attempts were generated in Windows security logs.
