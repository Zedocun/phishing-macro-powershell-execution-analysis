# MITRE ATT&CK Mapping

## Initial Access

### T1566.001 - Phishing: Spearphishing Attachment
A phishing email delivered a password-protected ZIP archive containing a malicious macro enabled document.

## Execution

### T1204.002 - User Execution: Malicious File
The user opened the delivered archive and the embedded document was executed.

### T1059.001 - Command and Scripting Interpreter: PowerShell
PowerShell was launched to run a command that attempted to download and execute a secondary file.

## Command and Control

### T1071.001 - Application Layer Protocol: Web Protocols
An HTTP request was made to retrieve a file from an external domain.

### T1071.004 - Application Layer Protocol: DNS
A DNS query was observed for `www.greyhathacker.net`.

## Defense Evasion

Not confirmed from available evidence.

## Persistence

Not confirmed from available evidence.

## Exfiltration

Not confirmed from available evidence.

## Impact

Not confirmed from available evidence.
