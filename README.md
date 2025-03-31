 active-directory-Project
This project sets up an Active Directory (AD) lab using VirtualBox to simulate a domain environment. It demonstrates user management, organizational units (OUs), group policies (GPOs), and security settings for better Windows network administration.

Lab Setup

VMs Used:

Windows Server 2022 (Domain Controller - DC)

Windows 11 (Domain-joined client)

Network Configuration:

Both VMs are set to the same VirtualBox network.

Windows 11 DNS set to the DC IP for domain connectivity.

Active Directory Configuration :

Installed AD DS Role & Promoted the Server to a Domain Controller.

Created Organizational Units (OUs):

IT: Tim (User) & Sam (Windows 11 VM )

HR: Matt & Sarah (Users)

Added Users & Applied Policies:

Users are forced to change passwords on the first login.

The password policy (length & expiration rules) was enforced.

Joined Windows 11 Machine to the Domain.

Group Policy Management (GPOs):

Password Policy: Enforced strong password requirements. ( for the whole domain )

Disabled USB access ( HR Department )

HR Policy:
Password Policy: Enforced strong password requirements.

 Blocked USB device usage.

Issues Faced & Solutions:

Network Connectivity Issues → Fixed by setting the correct VirtualBox network mode & DNS settings.

Windows 11 Losing Network → Resolved by adjusting DNS & IP settings.
Password Policy: Enforced strong password requirements.

Lessons Learned :

Hands-on experience with Active Directory & Group Policy.

Troubleshooting network & user login issues.

Importance of correct DNS settings in a domain environment.

Key Screenshots

"Please see screenshots"

