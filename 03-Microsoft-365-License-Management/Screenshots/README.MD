# Project 03 – Microsoft 365 License Management

## Overview

This project demonstrates Microsoft 365 license administration using the Microsoft 365 Admin Center. The lab focuses on reviewing license availability, verifying user licensing, reviewing licensed applications and services, removing a license, and reassigning it to a user.

License management is a common responsibility for IT Support and Microsoft 365 administrators, particularly during employee onboarding, offboarding, and access troubleshooting.

---

## Scenario

An IT administrator needs to review Microsoft 365 license utilization and manage licensing for an employee.

The administrator verifies the user's existing Microsoft 365 Business Premium license, reviews the associated services, temporarily removes the license to simulate license recovery, and then reassigns it to restore the user's Microsoft 365 services.

---

## Objectives

- Review Microsoft 365 license availability
- Verify a user's assigned license
- Review licensed applications and services
- Remove a Microsoft 365 license from a user
- Verify license recovery
- Reassign a Microsoft 365 license
- Verify the final licensing status

---

## Lab Environment

| Component | Details |
|----------|---------|
| Microsoft 365 Plan | Microsoft 365 Business Premium |
| Administration Portal | Microsoft 365 Admin Center |
| Identity Platform | Microsoft Entra ID |
| Lab User | Emma Wilson |
| Environment | Cloud-based Microsoft 365 Tenant |

---

## Project Structure

```text
03-Microsoft-365-License-Management
├── README.md
└── Screenshots
    ├── 01_License_Overview.png
    ├── 02_User_License_Assigned.png
    ├── 03_Licensed_Apps.png
    ├── 04_License_Removed.png
    ├── 05_License_Reassigned.png
    └── 06_Final_License_Status.png
```

---

## Lab Steps

1. Accessed the Microsoft 365 Admin Center.
2. Navigated to **Billing → Licenses**.
3. Reviewed Microsoft 365 Business Premium license availability and utilization.
4. Opened the Emma Wilson user account.
5. Reviewed the user's assigned Microsoft 365 Business Premium license.
6. Reviewed the applications and services associated with the license.
7. Removed the Microsoft 365 Business Premium license from the lab user.
8. Verified that the license was successfully removed.
9. Reassigned the Microsoft 365 Business Premium license.
10. Verified the user's final licensing status.

---

## License Overview

The Microsoft 365 Business Premium licensing dashboard was reviewed to identify available and assigned licenses.

![License Overview](Screenshots/01_License_Overview.png)

---

## User License Verification

The lab user's account was reviewed to confirm that Microsoft 365 Business Premium was assigned.

![User License Assigned](Screenshots/02_User_License_Assigned.png)

---

## Licensed Applications and Services

The applications and services associated with the Microsoft 365 Business Premium license were reviewed.

![Licensed Apps](Screenshots/03_Licensed_Apps.png)

---

## License Removal

The Microsoft 365 Business Premium license was temporarily removed from the lab user to simulate license recovery during an employee lifecycle administration scenario.

![License Removed](Screenshots/04_License_Removed.png)

---

## License Reassignment

The Microsoft 365 Business Premium license was reassigned to restore the user's access to licensed Microsoft 365 services.

![License Reassigned](Screenshots/05_License_Reassigned.png)

---

## Final License Verification

The licensing dashboard was reviewed again to verify the final license allocation after reassignment.

![Final License Status](Screenshots/06_Final_License_Status.png)

---

## Skills Demonstrated

- Microsoft 365 license administration
- Microsoft 365 Business Premium management
- User license assignment
- License removal and recovery
- License reassignment
- Microsoft 365 service management
- User lifecycle administration
- Microsoft 365 Admin Center navigation
- IT support troubleshooting

---

## Lessons Learned

- Microsoft 365 licenses determine which cloud services and applications are available to users.
- Administrators can centrally assign and remove licenses through the Microsoft 365 Admin Center.
- Removing a license makes it available for reassignment to another user.
- License management is an important component of employee onboarding and offboarding.
- Verifying licensing is an important troubleshooting step when users cannot access Microsoft 365 services.
- Proper license management helps organizations control service access and optimize available subscriptions.

---

## Next Project

**Project 04 – Exchange Online Administration**

The next project focuses on practical Exchange Online administration tasks, including mailbox management, aliases, shared mailboxes, mailbox permissions, and message tracing.