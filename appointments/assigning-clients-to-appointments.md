---
title: How to assign clients to appointments
audience: staff-web users
app: staff-web
category: appointments
last_updated: 2026-05-11
---

# How to assign clients to appointments

## Overview

When creating an appointment, you select the client after choosing the service. The client selection flow supports existing Wellpass clients, studio clients without a Wellpass account, and brand-new walk-in clients. After a client is selected, the system shows any eligible packages so you can apply one to the booking.

---

## How the client selection flow works

### Finding a client

After selecting a service in the **Create Appointment** modal, use the client search field to find the person you want to book.

- Type the client's name. Results appear as you type.
- Select the client from the list to confirm.

If the client does not appear in the results, a prompt allows you to add them as a new walk-in. See the walk-in section below.

> **Note:** Always search first before adding a new client. This prevents duplicate records if the same person has visited before.

### Walk-in clients

If a client cannot be found in the search results, you can add them as a walk-in entry. You will need to provide:

- First name
- Last name
- Phone number (required)

Walk-in clients do not have a Wellpass account. They will not receive push notifications. If a walk-in client later creates a Wellpass account using the same phone number, their appointment history is automatically linked to their new account.

---

## Applying a package

After the client is selected, a **Use a Package?** step appears if the client has eligible packages with sessions remaining.

- All eligible packages are listed.
- The first package in the list is pre-selected by default.
- To use a different package, select it from the list. The pre-selected package is deselected.
- To book without a package (as a cash booking), deselect all packages.

If the client has no eligible packages, this step is skipped entirely.

### What counts as an eligible package

A package appears in the list if it:
- Is currently active
- Has sessions remaining
- Is valid for appointment use

Expired packages and packages with no remaining sessions do not appear.

### Package vs. cash booking

| Booking type | What is recorded |
|---|---|
| Package applied | One session is deducted from the package. The appointment price is recorded as zero. |
| No package (cash) | The appointment is recorded at the listed service price (or the overridden price if changed). |

---

## Related

- [Creating an appointment](creating-an-appointment.md)
- [Managing a booked appointment](managing-a-booked-appointment.md)
