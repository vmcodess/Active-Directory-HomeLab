# Active Directory Homelab

## Overview
Built a small Active Directory environment with Windows Server 2019 and 1000 Windows 10 clients to simulate a corporate network. Practiced account management, group policies, and log monitoring.

## Tools Used
- VMware Workstation
- Windows Server 2019
- Windows 10 Pro
- Splunk Free Edition */ Not yet */

## Architecture
![Diagram](setup-diagram.png)

## Steps
1. Installed Windows Server and promoted it to a domain controller.
2. Configured DNS and DHCP.
3. Script added 1000 client machines to the domain.
4. Created users and applied Group Policy (password complexity, lockout). (have to do this **)

## Results
- Verified login restrictions.
- Captured failed login attempts in Splunk. ??? no
- Learned how Group Policy enforces security at scale.

## Future Improvements
- Add pfSense firewall and route traffic.
- Create SIEM alerts for brute-force attempts.