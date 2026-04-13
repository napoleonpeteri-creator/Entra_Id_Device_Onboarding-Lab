Entra ID Device Onboarding Lab

Overview

This project demonstrates how to create a Windows virtual machine using Hyper-V and onboard it into Microsoft Entra ID for enterprise identity management.



Lab Setup

Hyper-V Virtual Machine Creation

![VM Creation](screenshots/vm_creation.png)



Specify Name and Location

![Name and Location](screenshots/SPECIFY_NAME_AND_LOCATION.png)



Assign Memory

![Memory](screenshots/ASSIGN_MEMORY.png)


 Configure Network

![Network](screenshots/network_config.png)



Configure Virtual Hard Disk

![Disk](screenshots/virtual_harddisk_connect.png)



Windows Installation

Start Windows Installation

![Windows Install](screenshots/windows_install.png)



 Operating System Installation Process

![OS Install](screenshots/operating_system_install.png)


 Entra ID Integration

 Access Work or School (Before Join)

![Before Join](screenshots/BEFORE_JOINING_DEVICE_TO_MICROSOFT_ENTRA_ID.png)



Initiate Entra ID Join

![Initiating Join](screenshots/INITIATING_ENTRA_ID_JOIN.png)


 User Authentication

![Authentication](screenshots/authentication.png)


 Confirm Organization Join

![Confirmation](screenshots/confirmation.png)


 Device Successfully Joined

![Join Success](screenshots/join_success.png)



 Additional Join Confirmation

![Join Success 2](screenshots/join_success (2).png)



 Verification

 Verify Device Registration (dsregcmd)

![Verification](screenshots/dsregcmd_verification.png)



 Tenant Details Confirmation

![Tenant Details](screenshots/tenant_details.png)



 RBAC Observation

 Intune Access Restriction

![Intune Error](screenshots/intune_access_error.png)



 Key Takeaway

This lab demonstrates practical enterprise device onboarding and highlights how RBAC policies can restrict access even after a successful device join.
Access should be granted by intune Admin.
