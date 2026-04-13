Entra ID Device Onboarding Lab

Overview
This project demonstrates how to create a Windows virtual machine using 
Hyper-V and join it to Microsoft Entra ID for enterprise identity management.



 Lab Setup
. Hyper-V Virtual Machine
. Windows OS Installation
. Default Switch Networking



 Entra ID Integration
. Device joined to Microsoft Entra ID
. Authentication using organizational account
. Device registered successfully



 Verification

Command used: dsregcmd /status



Result:
. AzureAdJoined: YES
. DeviceAuthStatus: SUCCESS



 RBAC Observation

While accessing Microsoft Intune:

. Encountered **"Unauthorized" error**
. Cause: Insufficient permissions (RBAC)

This demonstrates real-world access control limitations in enterprise environments.



Screenshots


![Memory](screenshots/ASSIGN_MEMORY.png)
![Network](screenshots/network_config.png)
![Disk](screenshots/virtual_harddisk_connect.png)
![Windows Install](screenshots/windows_install.png)
![Authentication](screenshots/authentication.png)
![Initiating Join](screenshots/INITIATING_ENTRA_ID_JOIN.png)
![Confirmation](screenshots/confirmation.png)
![Join Success](screenshots/join_success.png)
![Join Success 2](screenshots/join_success (2).png)
![Verification](screenshots/dsregcmd_verification.png)
![Tenant Details](screenshots/tenant_details.png)
![Intune Error](screenshots/intune_access_error.png)
![Name and Location](screenshots/SPECIFY_NAME_AND_LOCATION.png)
![VM Creation](screenshots/vm_creation.png)
![OS Install](screenshots/operating_system_install.png)


Skills Demonstrated
. Virtualization (Hyper-V)
. Windows Deployment
. Microsoft Entra ID Integration
. Device Identity Verification
. RBAC Troubleshooting



