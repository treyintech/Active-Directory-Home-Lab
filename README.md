# ACTIVE DIRECTORY HOME LAB

## Objective

The objective of this project was to design and deploy a fully functional Active Directory home lab using Oracle VirtualBox, Windows Server 2025, and Windows 11. Through this implementation, I aimed to strengthen my understanding of enterprise Windows networking by configuring a Domain Controller, Active Directory Domain Services (AD DS), DNS, DHCP, NAT/Routing, and domain-joined client systems. Additionally, I leveraged PowerShell automation to create and manage user accounts at scale, gaining hands-on experience with common IT administration tasks and simulating a real-world corporate network environment.

### Skills Learned

- Active Directory Administration
- Windows Server 2025
- Windows 11 Administration
- PowerShell Automation
- DNS & DHCP Configuration
- Network Address Translation (NAT)
- Routing and Remote Access Services (RRAS)
- Virtualization (Oracle VirtualBox)
- Identity & Access Management (IAM)
- User & Group Management
- Network Troubleshooting
- Enterprise Windows Networking
- Domain Controller Management
- Active Directory User Provisioning
- IT Infrastructure Administration

### Tools Used

- Oracle VirtualBox – Created and managed virtual machines for the lab environment.
- Windows Server 2025 – Served as the Domain Controller and hosted core network services.
- Windows 11 Pro – Configured as a domain-joined client workstation.
- Active Directory Domain Services (AD DS) – Managed users, computers, and domain resources.
- Windows Server Manager – Installed and managed server roles and features.
- PowerShell – Automated bulk user account creation and administrative tasks.

## Steps



*Step 1: Built the Virtual Lab Environment*
- Installed Oracle VirtualBox and configured virtualization settings.
- Downloaded and prepared Windows Server 2025 and Windows 11 installation media.
- Created separate virtual machines for the Domain Controller and client workstation.
  <img width="1229" height="640" alt="image" src="https://github.com/user-attachments/assets/0740d7b3-f73a-482b-8af9-318f6898990c" />

*Step 2: Configured the Domain Controller*
- Installed Windows Server 2025.
- Configured dual network adapters for internet access and an isolated internal network.
- Assigned static IP addressing to the internal network interface.
- Renamed the server and prepared it for domain services.
  
*Step 3: Deployed Active Directory Domain Services (AD DS)*
- Installed the Active Directory Domain Services role.
- Promoted the server to a Domain Controller.
- Created a new Active Directory forest and domain.
- Configured Organizational Units (OUs) and administrative accounts.

*Step 4: Implemented Core Network Services*
- Installed and configured DNS for domain name resolution.
- Installed and configured DHCP to automatically assign IP addresses to client systems.
- Created a DHCP scope and configured gateway and DNS options.
- Verified client network connectivity and address assignment.

*Step 5: Configured Routing and Internet Access*
- Installed Routing and Remote Access Services (RRAS).
- Configured Network Address Translation (NAT) to provide internet connectivity for internal network devices.
- Tested external connectivity and DNS resolution from client systems.
  
*Step 6: Automated User Provisioning*
- Utilized PowerShell scripting to automate Active Directory administration.
- Created an Organizational Unit for user accounts.
- Generated and imported over 1,000 Active Directory user accounts through a bulk provisioning script.
- Verified successful account creation and directory structure.
<img width="1170" height="720" alt="path3" src="https://github.com/user-attachments/assets/596de322-a507-41cc-b5cd-4a97353a616f" />

*Step 7: Deployed and Configured a Client Workstation*
- Installed Windows 11 Pro on a separate virtual machine.
- Connected the workstation to the internal virtual network.
- Obtained network configuration through DHCP.
- Renamed the workstation and joined it to the Active Directory domain.
  
*Step 8: Validated Authentication and Network Services*
- Logged into the client workstation using domain credentials.
- Verified Active Directory authentication and user profile creation.
- Confirmed DNS functionality, internet access, and domain communication.
- Validated DHCP leases and Active Directory computer object creation.
<img width="1655" height="747" alt="path2" src="https://github.com/user-attachments/assets/a27d139c-63a5-4dcc-b598-822ee16a39dd" />

## Project Outcome

Successfully built and administered a simulated enterprise Windows environment that included Active Directory, DNS, DHCP, NAT, and domain-joined client systems. Through this project, I gained hands-on experience managing user accounts, configuring network services, automating administrative tasks with PowerShell, troubleshooting connectivity issues, and supporting core infrastructure components commonly found in corporate IT environments. The completed lab strengthened my understanding of identity management, system administration, desktop support, and enterprise networking concepts.
