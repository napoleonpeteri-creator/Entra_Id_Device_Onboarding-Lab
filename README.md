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

### VM Creation
![VM Creation](screenshots/01-vm-creation.png)

### Memory Configuration
![Memory](screenshots/02-assign-memory.png)

### Network Setup
![Network](screenshots/03-network-config.png)

### Windows Installation
![Windows Install](screenshots/04-windows-install.png)

### Entra Join Initiation
![Join Start](screenshots/05-entra-join-init.png)

### Authentication
![Auth](screenshots/06-authentication.png)

### Confirmation
![Confirm](screenshots/07-confirmation.png)

### Join Success
![Success](screenshots/08-join-success.png)

### Verification (dsregcmd)
![Verification](screenshots/09-dsregcmd-verification.png)

### Tenant Details
![Tenant](screenshots/10-tenant-details.png)

### Intune Access Error
![RBAC](screenshots/11-intune-access-error.png)



Skills Demonstrated
. Virtualization (Hyper-V)
. Windows Deployment
. Microsoft Entra ID Integration
. Device Identity Verification
. RBAC Troubleshooting



 Next Steps
. Intune Enrollment
. Sysmon Installation
. Log forwarding to Splunk

