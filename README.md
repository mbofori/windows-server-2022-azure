# Deploying Windows Server 2022 on Microsoft Azure

## Project Overview
This project demonstrates the deployment and initial configuration of a Windows Server 2022 virtual machine on Microsoft Azure. 
The goal was to gain hands-on experience with cloud-based server infrastructure and understand how traditional server administration concepts translate into a cloud environment.

The project focuses on core areas such as virtual machine provisioning, Azure networking, secure access configuration, and basic system validation, with an emphasis on reliability, security, and clear documentation.

---

## Objectives
- Deploy a Windows Server 2022 virtual machine using Microsoft Azure  
- Configure basic Azure networking and security controls  
- Secure and validate remote access to the server  
- Perform initial server setup and updates  
- Document the deployment process and key configuration decisions  

---

## Technologies Used
- Microsoft Azure  
  - Azure Virtual Machines  
  - Resource Groups  
  - Virtual Networks & Subnets  
  - Network Security Groups (NSGs)  
- Windows Server 2022  
- Remote Desktop Protocol (RDP)

---

## Architecture Overview
The deployment follows a simple and practical cloud architecture:

- A dedicated Resource Group to manage all related resources  
- A Windows Server 2022 VM deployed in a selected Azure region  
- An Azure Virtual Network (VNet) with a defined subnet  
- Network Security Group (NSG) rules to control inbound and outbound traffic  
- Secure remote access via RDP  

---

## Architecture Diagram
![Windows Server 2022 on Azure Architecture](screenshots/architecture-diagram.png)

---

## Implementation Steps
1. Created an Azure Resource Group to organize project resources  
2. Provisioned a Windows Server 2022 Virtual Machine  
3. Configured VM size, storage options, and region  
4. Set up a Virtual Network and subnet  
5. Applied Network Security Group rules to control access  
6. Configured secure RDP access  
7. Completed initial Windows Server setup, updates, and validation  
8. Verified connectivity and system availability  

---

## Security Considerations
- Restricted inbound access using Network Security Groups  
- Limited RDP exposure to required access only  
- Applied system updates after deployment  
- Followed basic cloud security best practices during setup  

---

## Lessons Learned
- How Azure virtual machines are provisioned and managed  
- The relationship between Azure networking components and VM connectivity  
- The importance of security controls at the network level  
- How on-premises server administration concepts apply in cloud environments  
- The value of documentation for repeatability and troubleshooting  

---

## Future Improvements
- Join the server to an Active Directory domain  
- Implement Azure Backup or snapshot-based recovery  
- Add monitoring and logging using Azure Monitor  
- Apply role-based access control (RBAC)  
- Automate deployment steps using scripts or templates  

---

## Author
**Michael Bannor Ofori**  
MEng Internetworking  
Interested in Networking, Systems, Cloud Infrastructure, and Digital Transformation
