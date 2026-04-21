# Indicators of Compromise (IOCs)

## File Names

- `edit1-invoice.docm.zip`
- `edit1-invoice.docm`
- `messbox.exe` *(attempted download)*
- `mess.exe` *(attempted execution via command line)*

## File Hash

- `1a819d18c9a9de4f81829c4cd55a17f7674433c22f9b30ca953866827e5d96fb0`

## Email Indicators

- Sender: `jake.admin@cybercommunity.info`
- Recipient: `jayne@letsdefend.io`
- Subject: `February Membership Fee`

## Domains

- `www.greyhathacker.net`
- `cybercommunity.info`

## URLs

- `http://www.greyhathacker.net/tools/messbox.exe`

## IP Addresses

- `92.204.221.16`

## Notes

- `edit1-invoice.docm` was flagged as malicious by multiple vendors.
- `www.greyhathacker.net` showed low reputation in reputation tooling.
- `cybercommunity.info` also showed suspicious / malicious reputation signals in reputation tooling.

## Caution

The presence of `messbox.exe` and `mess.exe` is supported by command-line and script block evidence.  
Successful download or execution of the secondary payload was **not confirmed** in the investigated environment.
