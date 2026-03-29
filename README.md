# Windows-Server-2022-Home-Lab-Active-Directory-Domain-Controller

📖 Project Overview  This project documents my hands-on experience building a Windows Server 2022 home lab using VirtualBox, where I promoted a server to a Domain Controller and configured Active Directory Domain Services (AD DS). 
The goal of this lab was to gain practical, real-world experience with:

- Windows Server administration
- Active Directory fundamentals
- User and group management
- Identity and access troubleshooting

🛠️ Initial Setup
I began by installing Windows Server 2022 on a VirtualBox virtual machine. As part of the foundational configuration, I assigned a static IP address to ensure the server’s stability before promoting it to a Domain Controller.

✅ Step 1: Assign a Static IP Address

Configured a static IP to ensure Domain Controller reliability
Defined the following network settings:
- IP Address
- Subnet Mask
- Preferred DNS (pointing to the server itself)

📸 Screenshot will be added

💡 Why this matters:
Domain Controllers require a static IP address to avoid authentication failures and DNS resolution issues within an Active Directory environment.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ Step 2: Install Active Directory Domain Services (AD DS)

- Opened Server Manager
- Added the Active Directory Domain Services role
- Included required features (DNS, Management Tools)

📸 Screenshot will be added
---------------------------------------------------------------------------------------------------------------------------------------------
💡 Steps (3-7): This lab helped me better understand user management, group policies, and real-world Active Directory workflows used in enterprise environments.
-------------------------------------------------------------------------------------------------------------------------------------
✅ Step 3: Promote Server to Domain Controller

- Promoted the server to a Domain Controller
- Created a new Active Directory domain
- Configured DNS and Domain Controller options
- Completed promotion and rebooted the server

📸 Screenshot will be added
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ Step 4: Installed Active Directory Domain Services (AD DS)

- Configured server roles and features
- Promoted the server to a Domain Controller
- Domain Controller name: DC01

📸 Screenshot will be added
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ Step 5: Created and Managed Users

- Added user accounts: Joe Doe and Jalen Burnson
- Configured accounts to require a password change at next logon
- Demonstrated secure onboarding practices

📸 Screenshot will be added
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ Step 6: Organized Users with Groups

- Created departmental groups: Finance and HR
- Assigned users to appropriate groups for better access control

📸 Screenshot will be added
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ Step 7: Tested User Authentication

- Logged in as a test user (John Doe)
- Verified system prompt requiring password change before first login
- Confirmed domain authentication is working as expected

📸 Screenshot will be added
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
