# SOC Investigation

## Alert Trigger

Multiple failed login attempts detected.

## Log Analysis

Windows Security Logs show:

Event ID 4625 – Failed login attempts  
Event ID 4624 – Successful login  

Source IP: 192.168.56.101

## Timeline

10:10 PM – Network scan detected  
10:12 PM – Multiple failed login attempts  
10:14 PM – Successful login  

## Conclusion

The system experienced a brute force attack targeting the SMB service.
