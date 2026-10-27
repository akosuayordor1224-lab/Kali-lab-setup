

Kali Lab Setup

I built a fully isolated penetration testing lab from scratch. I configured VirtualBox 7.x with a custom NAT Network (10.0.0.0/24 - NatNetwork) and deployed Kali Linux 2026.2 using a 15GB VDI.

**Key Troubleshooting Steps:**
- Bypassed a direct download speed of 16 KB/s (with a 3-day ETA) by switching to qBittorrent P2P, achieving speeds of over 400 KB/s.
- Resolved issues with "Inaccessible" storage and "Invalid settings detected" by cleaning up duplicate SATA attachments and re-linking the VDI.
- Fixed a UUID conflict by recreating the VM and attaching the existing disk.
- Verified lab isolation: Adapter 1 (NAT Network) with IP address 10.0.0.3 is successfully connected.

This setup provides a reproducible, snapshot-ready environment for cybersecurity training.
