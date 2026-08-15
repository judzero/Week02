# WEEK 02 08/15/2026
# Projet Overview
This project presents a complete IT infrastructure plan for ABC Startup Solutions, a fictional software development startup with 20 employees operating from a single office floor.

The infrastructure is designed from zero and includes:

- Company and organizational profile
- Hardware inventory
- Software inventory
- Network inventory
- Network architecture and Draw.io specification
- System administration roles
- Infrastructure and security recommendations
- Personal reflection

The overall design prioritizes reliability, security, scalability, manageable costs, and future expansion.

# Learning Objectives
This project demonstrates the ability to:

1. Analyze an organization's IT infrastructure requirements.
2. Design an appropriate hardware inventory.
3. Select operating systems and business software.
4. Design a segmented enterprise network.
5. Understand VLANs, routing, switching, and firewall placement.
6. Develop backup and security strategies.
7. Understand system administration responsibilities.
8. Plan infrastructure for future business growth.
9. Document an IT environment professionally.
10. Reflect on the skills developed through infrastructure planning.

# Company Scenario
### Company Name
**ABC Startup Solutions**

### Nature of Business

ABC Startup Solutions is a fictional software development company that provides software development, testing, consulting, integration, and technical support services.

### Office

Unit 402, Innovation Tower  
J.P. Laurel Avenue  
Barangay San Antonio, Makati City  
Metro Manila, Philippines
### Employee Distribution

| Department | Employees |
|---|---:|
| Information Technology | 5 |
| Human Resources | 4 |
| Finance | 5 |
| Sales | 6 |
| **Total** | **20** |

---
## Hardware Inventory Summary

The infrastructure provides exactly one primary computer for each of the 20 employees.

| Hardware | Quantity |
|---|---:|
| Desktop Computers | 14 |
| Laptops | 6 |
| Server | 1 |
| Router | 1 |
| Managed 48-Port Switch | 1 |
| Network Printer | 1 |
| UPS | 3 |
| Wireless Access Points | 2 |
| NAS Storage | 1 |
| External Backup Drives | 2 |
| Monitors | 24 |
### Computer Allocation

| Department | Desktops | Laptops | Total Computers |
|---|---:|---:|---:|
| IT | 3 | 2 | 5 |
| HR | 4 | 0 | 4 |
| Finance | 5 | 0 | 5 |
| Sales | 2 | 4 | 6 |
| **Total** | **14** | **6** | **20** |

The additional monitors provide dual-display capability for development, administration, financial analysis, and other productivity-intensive work.

---
## Software Inventory Summary

| Software | Version/Baseline | Main Purpose |
|---|---|---|
| Windows 11 Pro | 25H2 | Employee operating system |
| Ubuntu Server | 24.04.4 LTS | Server operating system |
| Microsoft 365 Apps | Current Channel, Version 2606 baseline | Office productivity |
| Visual Studio Code | Current Stable | Software development |
| Git | Current Stable | Version control |
| GitHub Desktop | Current Stable | Graphical Git workflow |
| VirtualBox | Current Stable | Virtual machines/testing |
| Google Chrome | Current Stable | Web applications |
| Microsoft Defender | Current | Endpoint security |
| AnyDesk | Current business release | Authorized remote support |
| 7-Zip | Current Stable | File compression |

---

## Challenges Encountered
The main challenge was maintaining consistency between all infrastructure components.
The employee count had to match the endpoint inventory, while the network design needed to accommodate all computers, servers, storage, printers, wireless access points, and network equipment.
Another challenge was designing a network that was simple enough for a 20-person startup but structured enough to support security and future growth. VLAN segmentation was selected to separate IT, HR, Finance, Sales, infrastructure, corporate wireless, and guest wireless traffic.
Security planning was also important because the company was starting without existing security policies. The design therefore incorporates firewalls, endpoint protection, BitLocker, MFA, least privilege, VLAN isolation, secure administration, and offline backups.

