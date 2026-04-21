# Investigation Timeline

## Feb 28, 2024

**08:12 AM**  
Phishing email delivered to `jayne@letsdefend.io` from `jake.admin@cybercommunity.info` with subject:
`February Membership Fee`

**08:12 AM**  
Attachment observed:
`edit1-invoice.docm.zip`  
Password provided in email body: `infected`

**08:41 AM**  
File creation event shows:
`C:\Users\LetsDefend\Downloads\edit1-invoice.docm.zip`

**08:42 AM**  
Alert generated:
`SOC205 - Malicious Macro has been executed`

**08:42 AM**  
Process creation event shows:
`WINWORD.EXE` opening `edit1-invoice.docm`

**08:42 AM**  
Process creation event shows:
`powershell.exe`

**08:42 AM**  
PowerShell command attempts to:
- download `messbox.exe` from `www.greyhathacker.net`
- save/launch `mess.exe`

**08:42:51 AM**  
DNS query observed for:
`www.greyhathacker.net`

**08:42 AM**  
HTTP GET request observed for:
`http://www.greyhathacker.net/tools/messbox.exe`

**08:42 AM**  
HTTP response code:
`404`

## Containment

Host containment action was later applied.

## Summary

The timeline confirms phishing delivery, document execution, and PowerShell activity.  
The secondary payload download attempt is visible, but successful payload execution is **not confirmed**.
