# Incident Report

## Incident Summary

A brute force attack was detected against a Windows 10 machine.

## Affected System

Host: Windows 10
Service: SMB (Port 445)

## Attack Source

IP Address: 192.168.56.101

## Evidence

Event ID 4625 – Failed login attempts  
Event ID 4624 – Successful login  

## Risk Level

Medium to High

## Recommended Actions

- Disable SMB externally
- Enable account lockout policy
- Monitor authentication logs
