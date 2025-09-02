# rkct
# Remote Kernel Configuration Tool (RKCT)

RKCT is designed to remotely manage and configure Linux kernel parameters via the `/proc/sys` interface from a centralized server.

## Structure
- **server/** → Flask/Express server + dashboard
- **client/** → C/Bash daemon for /proc/sys
- **certs/** → TLS/SSL certificates
- **docs/** → Diagrams, documentation

## Goal
Securely manage kernel parameters:
- Read/write `/proc/sys`
- Authentication & authorization
- Logging & auditing
- Real-time monitoring


