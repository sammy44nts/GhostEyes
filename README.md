# GhostEyes v2 - Offensive Reconnaissance Toolkit

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License: GPLv3](https://img.shields.io/badge/License-GPLv3-yellow)](https://github.com/6lackRaven/GhostEyes?tab=License-1-ov-file)
[![GitHub stars](https://img.shields.io/github/stars/6lackRaven/GhostEyes?style=social)](https://github.com/6lackRaven/GhostEyes)

<p align="center">
  <img src="https://private-user-images.githubusercontent.com/202351661/469445619-d59c7e15-68e7-4b9b-9077-0dc9b0bce7d7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTMyMTc5MDYsIm5iZiI6MTc1MzIxNzYwNiwicGF0aCI6Ii8yMDIzNTE2NjEvNDY5NDQ1NjE5LWQ1OWM3ZTE1LTY4ZTctNGI5Yi05MDc3LTBkYzliMGJjZTdkNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNzIyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDcyMlQyMDUzMjZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jNjRmMGEwNTlhNjg2MGYxN2EzZTUzMjU1M2RlYzUyM2M2ZDQzOTM3MTQwYzI4ZjMwYzM1Y2M5OTUyOTVmZmFkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.lQHvP2_IooXSQb_qoU5lLvclF41BzyT2XmczgFfh-F4" width="250"/>
</p>

# GhostEyes 👁️  
Advanced network recon tool built with Python.
Advanced cybersecurity toolkit for network reconnaissance, vulnerability discovery, and penetration testing.

## Features
- Network scanning & host discovery
- VLAN hopping & Layer 2 attacks
- Web reconnaissance (subdomains, directories, tech stack)
- Real-time device tracking
- Multi-format reporting

## Installation
```bash
git clone https://github.com/6lackRaven/GhostEyes.git
cd GhostEyes
pip install -r requirements.txt
```

## Usage

# Network scanning
sudo ./ghosteyes.py net --scan 192.168.1.0/24

# VLAN discovery
sudo ./ghosteyes.py net --vlan --duration 60

# Web reconnaissance
./ghosteyes.py web --url https://example.com --tech

# Generate reports
./ghosteyes.py report --file scan_web.json --type html

## Modules
Command | Function |
|---------|----------|
| `net --scan` | ARP subnet scanning |
| `net --vlan` | VLAN discovery |
| `net --trace` | Layer 2 traceroute |
| `web --subdomains` | Subdomain enumeration |
| `web --bruteforce` | Directory brute-forcing |

## Disclaimer

## LEGAL NOTICE
GhostEyes is developed for **AUTHORIZED SECURITY TESTING AND LEGITIMATE EDUCATIONAL PURPOSES ONLY**.

🚨 **WARNING: UNAUTHORIZED USE IS ILLEGAL**
- You must have explicit written permission to scan or test any network or system
- You are solely liable for any misuse of this toolkit
- Developers assume no responsibility for unauthorized or illegal use

## ETHICAL GUIDELINES
1. **Always obtain proper authorization** before using GhostEyes
2. **Never target systems** you do not own or have permission to test
3. **Respect privacy** - Do not access or collect personal data
4. **Comply with all applicable laws** (Computer Fraud and Abuse Act, GDPR, etc.)

## PROFESSIONAL USE
GhostEyes should only be used by:
- Certified security professionals
- Penetration testers with valid contracts
- Security researchers with explicit permissions
- Educational institutions in controlled environments

By using this software, you acknowledge that:
- You understand these terms
- You accept full liability for your actions
- The developers bear no responsibility for misuse

## LICENSE

GhostEyes is released under the GNU General Public License v3.0 or later.  
See the [LICENSE](./LICENSE) file for details.

## Contact

If you have any questions, suggestions, or want to collaborate, feel free to reach out:

- **Email:** harleystanislas.raven@gmail.com  
- **GitHub:** [https://github.com/6lackRaven](https://github.com/6lackRaven)  
- **FaceBook:** [Harley Stanislas](https://www.facebook.com/profile.php?id=100087273507449)  
---

## Support

If you find this project useful, you can support me by:

- ⭐️ Starring the repository  
- Sharing the project with your network  
- [Sponsoring me on GitHub](https://github.com/sponsors/6lackRaven)  
- Reporting issues or contributing to the code

Thank you for your support!
