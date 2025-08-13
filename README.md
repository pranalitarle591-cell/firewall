# firewall
# Firewall Configuration and Testing

## Objective
Configure and test basic firewall rules to allow or block network traffic on Windows and Linux systems.

---

## Tools Used
- **Windows Firewall** (via Windows Defender Firewall with Advanced Security)
- **UFW (Uncomplicated Firewall)** on Ubuntu/Linux

---

## Setup and Configuration

### Windows Firewall

#### Enable and Configure
1. Open **Control Panel > System and Security > Windows Defender Firewall**.
2. Click on **Advanced Settings** to access inbound/outbound rules.
3. Create new rules:
   - **Allow Rule**: Allow traffic on port 80 (HTTP).
   - **Block Rule**: Block traffic on port 21 (FTP).

#### Commands via PowerShell (optional)
```power
