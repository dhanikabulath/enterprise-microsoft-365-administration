# Project 04 – Exchange Online Administration

## Overview

This project demonstrates practical Exchange Online administration tasks using the Exchange Admin Center.

The lab focused on reviewing user mailboxes, configuring an email alias, creating a shared mailbox, assigning mailbox delegation permissions, reviewing mail flow rules, and using message trace for email troubleshooting.

---

## Scenario

An organization's IT department requires a shared mailbox for handling IT support communications.

As the Microsoft 365 administrator, the task is to review existing Exchange Online mailboxes, configure an additional email alias for a user, create an IT Support shared mailbox, delegate mailbox access, and review Exchange Online tools used for mail flow and delivery troubleshooting.

---

## Objectives

- Navigate the Exchange Admin Center
- Review Exchange Online user mailboxes
- Review mailbox properties
- Configure an SMTP email alias
- Create a shared mailbox
- Configure mailbox delegation
- Assign Full Access permissions
- Assign Send As permissions
- Review Exchange mail flow rules
- Review message tracing capabilities

---

## Lab Environment

| Component | Details |
|---|---|
| Microsoft 365 Plan | Microsoft 365 Business Premium |
| Administration Portal | Exchange Admin Center |
| Email Platform | Exchange Online |
| Identity Platform | Microsoft Entra ID |
| Environment | Cloud-based Microsoft 365 Tenant |

---

## Project Structure

```text
04-Exchange-Online-Administration
├── README.md
└── Screenshots
    ├── 01_Exchange_Mailboxes.png
    ├── 02_User_Mailbox.png
    ├── 03_Email_Alias.png
    ├── 04_Shared_Mailbox.png
    ├── 05_Mailbox_Delegation.png
    ├── 06_Mail_Flow_Rules.png
    └── 07_Message_Trace.png
```

---

## Lab Steps

1. Accessed the Exchange Admin Center.
2. Navigated to the Exchange Online mailbox administration interface.
3. Reviewed existing user mailboxes.
4. Opened the Emma Wilson mailbox and reviewed mailbox properties.
5. Added an additional SMTP email alias to the user account.
6. Retained the existing email address as the primary SMTP address.
7. Created an `IT Support` shared mailbox.
8. Configured mailbox delegation for the shared mailbox.
9. Assigned Full Access permissions to a lab user.
10. Assigned Send As permissions to the lab user.
11. Reviewed Exchange Online mail flow rules.
12. Reviewed the Message Trace interface used for email delivery troubleshooting.

---

## Exchange Online Mailboxes

The Exchange Admin Center provides centralized administration of user and shared mailboxes within Exchange Online.

Existing mailboxes were reviewed through the Recipients section.

![Exchange Mailboxes](Screenshots/01_Exchange_Mailboxes.png)

---

## User Mailbox Administration

The lab user's Exchange Online mailbox was reviewed to examine mailbox information and available administrative settings.

![User Mailbox](Screenshots/02_User_Mailbox.png)

---

## Email Alias Configuration

An additional SMTP email alias was configured for the lab user while retaining the existing email address as the primary SMTP address.

This demonstrates how administrators can provide users with additional email addresses without creating separate mailboxes.

![Email Alias](Screenshots/03_Email_Alias.png)

---

## Shared Mailbox

A shared mailbox named `IT Support` was created to provide a centralized mailbox for IT support communications.

Shared mailboxes allow multiple authorized users to access and manage messages sent to a common organizational email address.

![Shared Mailbox](Screenshots/04_Shared_Mailbox.png)

---

## Mailbox Delegation

Mailbox delegation permissions were configured for the IT Support shared mailbox.

The lab user was granted:

- Full Access / Read and Manage permissions
- Send As permissions

Full Access allows the authorized user to open and manage the shared mailbox.

Send As allows the authorized user to send messages that appear to originate from the shared mailbox.

![Mailbox Delegation](Screenshots/05_Mailbox_Delegation.png)

---

## Mail Flow Rules

The Exchange Online mail flow rules interface was reviewed.

Mail flow rules can be used by administrators to control how messages are processed based on organizational requirements and defined conditions.

![Mail Flow Rules](Screenshots/06_Mail_Flow_Rules.png)

---

## Message Trace

The Message Trace interface was reviewed as an Exchange Online troubleshooting tool.

Message trace can help administrators investigate whether messages were received, processed, delivered, or affected by mail flow conditions.

This is particularly useful when troubleshooting user reports involving missing or undelivered email.

![Message Trace](Screenshots/07_Message_Trace.png)

---

## Skills Demonstrated

- Exchange Online administration
- Exchange Admin Center navigation
- User mailbox administration
- SMTP email alias management
- Shared mailbox creation
- Mailbox delegation
- Full Access permissions
- Send As permissions
- Mail flow administration
- Message tracing
- Email delivery troubleshooting
- Microsoft 365 administration

---

## Lessons Learned

- Exchange Online mailboxes can be centrally administered through the Exchange Admin Center.
- SMTP aliases allow additional email addresses to be associated with an existing mailbox.
- An alias can be added without changing the user's primary email address.
- Shared mailboxes provide centralized email access for organizational teams and functions.
- Mailbox delegation allows administrators to control who can access and send messages from shared mailboxes.
- Full Access and Send As permissions provide different levels of mailbox functionality.
- Message trace is an important troubleshooting tool for investigating email delivery issues.
- Exchange Online administration is a common component of Microsoft 365 IT support.

---

## Next Project

**Project 05 – Microsoft Teams Administration**

The next project focuses on Microsoft Teams administration, including team management, membership, guest access, and Teams policies.

---

**Status:** Completed