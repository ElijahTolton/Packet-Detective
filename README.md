# Packet Detective
 
Packet Detective is a browser-based game where players solve security incidents by analyzing packet captures, DNS logs, email records, and other forensic artifacts.
 
The project started as a way to make networking concepts feel less abstract. Instead of learning what DNS tunneling or a TCP handshake is from slides, players encounter them while investigating realistic scenarios.
 
## Example Cases
 
### Stolen Midterm
 
A professor claims an exam was leaked before release.
 
Available evidence:
 
- Packet capture
- Mail server logs
- DNS records
 
Find out how the file was accessed and who was involved.
 
### Suspicious Employee
 
A company suspects someone is exfiltrating confidential data.
 
Available evidence:
 
- Firewall logs
- DNS logs
- Authentication history
 
Determine whether data was actually stolen.
 
## Features
 
- Browser-based investigations
- Packet capture viewer
- Searchable logs
- Evidence timeline
- Case report submissions
- Multiple difficulty levels
 
## Topics Covered
 
Cases may involve:
 
- TCP
- DNS
- HTTP
- HTTPS
- SMTP
- TLS
- QUIC
- VPNs
- Firewalls
 
No prior cybersecurity experience is required.
 
## Tech Stack
 
### Frontend
 
- Next.js
- TypeScript
- Tailwind CSS
 
### Backend
 
- Supabase
- PostgreSQL
 
 
## Motivation
 
Most networking labs tell students exactly what to look for.
 
Packet Detective does the opposite.
 
The player gets a collection of evidence and a problem statement. Everything else has to be figured out from the data.
 
```
 
Built because reading Wireshark traces is more interesting when someone has committed a crime.
