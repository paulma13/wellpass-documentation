---
title: How to add a client to a class session
audience: staff-web users
app: staff-web
category: classes
last_updated: 2026-05-22
---

# How to add a client to a class session

## Overview

Use this when a client walks in, calls ahead, or asks you to add them to a class — whether they are an existing member, a returning client without an account, or someone brand new to your studio. This covers manually booking, registering, or signing up a client for a specific session directly from the calendar, without the client needing to do anything themselves. You can also use this to put a client on the waitlist when the session is already full. It works for any type of client: Wellpass account holders, previous clients you already have on file, and first-time walk-ins you are adding on the spot.


## How to add a client to a class session

### Step 1 — Open the session

1. Go to **Calendar** in the left sidebar.
2. Click the class session card for the session you want to manage.
3. The **session detail panel** opens on the right.

### Step 2 — Open the add-client flow

1. In the session detail panel, click **Add client**.
2. The **Add client** modal opens.

### Step 3 — Find the client

Use the search field to find the client you want to add.

- Type the client's name. Results appear as you type.
- Select the client from the list to confirm their identity.

If the client does not appear in the search results, a **Did not find client?** prompt appears. Click it to open the add-client form.

### Step 3a — Fill in the client's details (new walk-in only)

Complete the form with the client's information:

- **First name** (required)
- **Last name** (required)
- **Email** (optional)
- **Phone** (required) — select the country code from the dropdown, then enter the number

> **Note:** Always search before adding a new client. This prevents duplicate records when the same person attends again in the future.

### Step 3b — Confirm the phone number

After filling in the form, the system shows the phone number you entered in large text and asks you to confirm it before continuing. This step exists to catch typos — the phone number is how the system identifies clients across visits.

- Click **Confirm** to proceed.
- Click **Edit** to go back and correct the number.

### Step 3c — Wellpass account check (if applicable)

After you confirm the phone number, the system checks whether it belongs to an existing Wellpass account.

**If a Wellpass account is found:** the system shows "Wellpass user found on app: **[first name]**" and asks "Is this the correct person for the phone number you entered?"

- Click **Yes, confirm** — the client is linked to their Wellpass account. Their profile will show the **Wellpass Account** chip.
- Click **No, go back** — you return to the form to correct the phone number.

The system shows the first name only (not the full name) to protect the privacy of other Wellpass users.

**If no Wellpass account is found:** the client is added as a new walk-in immediately and the booking proceeds.

### Step 4 — Select a package (if applicable)

If the client has an active package with sessions remaining that applies to classes, the modal shows a **Use a package?** step.

- The eligible package is listed with its name and remaining session count.
- Click the package to select it. A **Selected** indicator appears.
- To book without using a package, leave the package unselected. The booking is recorded as cash.

If the client has no eligible class packages, this step is skipped and the booking proceeds directly.

### Step 5 — Confirm the booking

Click **Add to class** to confirm. The client is added to the session roster immediately and appears in the booking list on the session detail panel.



## Settings and options

### Walk-in clients

Walk-in clients are added with their name and phone number only — they do not need a Wellpass account. If a walk-in client later creates a Wellpass account using the same phone number, their booking history is automatically linked to their new account.

Walk-in clients do not receive push notifications because they have no app account.

### Package use

When a package is applied, the booking is recorded with a price of zero. When no package is applied, the booking is recorded at the session's listed price. If the session has no price set, the price is recorded as zero.

Only active packages that have sessions remaining and are enabled for class use appear in the package selection step.

### Waitlist

If the session is full, the **Add client** button adds the client to the waitlist instead of the roster. The client's position on the waitlist is shown in the booking list. If a spot opens up because another client cancels, the first person on the waitlist is notified automatically (Wellpass clients only).



## Edge cases

| Situation | What happens |
|||
| Client is already booked for this session | The modal shows an error: "This client is already booked for this class." No duplicate booking is created. |
| Session is full | The client is offered a place on the waitlist instead. |
| Client has a package but it is expired or has no sessions remaining | The expired or depleted package does not appear in the package selection step. The booking proceeds as cash. |
| New walk-in client has no Wellpass account | The package step is skipped entirely. A brand-new walk-in has no package history, so there is nothing to apply. |



## Related

- [Creating class sessions](creating-class-sessions.md)
- [Editing a class session](editing-a-class-session.md)
