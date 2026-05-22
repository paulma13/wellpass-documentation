---
title: How clients are added to your studio
audience: staff-web users
app: staff-web
category: clients
last_updated: 2026-05-22
---

# How clients are added to your studio

## Overview

Clients appear in your studio's client list when they are booked into a class or appointment. There is no separate "add client" screen — every client entry is created through a booking. This applies whether you are booking them into a class session from the calendar or creating an appointment for them from the appointments view.

## The three identity scenarios

When you add a client during a booking, the system works through a short flow to identify who they are. There are three possible outcomes.

### Scenario A — Client found by name search

You type the client's name in the search field. Their name appears in the results. You click **Add** next to their name, confirm their identity on the next screen, and the booking proceeds. No new record is created — the client is matched to their existing record.

This is the most common scenario for returning clients.

### Scenario B — Client not found, no Wellpass account

You search for the client by name and they do not appear. You click **Did not find the client?** to open the add form. You enter their first name, last name, phone number, and optionally their email address.

After filling in the form, the system shows you the phone number you entered in large text and asks you to confirm it before proceeding. This step exists to catch typos — phone numbers are how the system identifies clients across visits.

If the phone number you entered does not match any existing Wellpass account, the client is added immediately as a new walk-in. Their record is created and the booking proceeds.

### Scenario C — Client not found, Wellpass account discovered

The flow starts the same as Scenario B: you search, the client is not found, you fill in the form, and you confirm the phone number.

After you confirm the phone, the system checks whether that number belongs to a Wellpass account. If it does, the system shows: "Wellpass user found on app: **[first name]**" and asks "Is this the correct person for the phone number you entered?"

- If you click **Yes, confirm**, the client is linked to their Wellpass account. Their profile will show the **Wellpass Account** chip and they will see the booking in their app.
- If you click **No, go back**, you return to the form to re-enter the phone number or make a correction.

This confirmation step uses the first name only — not the full name — to protect the privacy of other Wellpass users.

## After the client is identified

Once the client's identity is resolved, the booking flow continues. If the client has any active packages with sessions remaining that apply to the class or appointment type, you are given the option to apply one before the booking is confirmed. If no eligible packages exist, the booking proceeds directly.

## Why this matters

Because every client is added through a booking, duplicate records are less likely than in systems with a manual add-client form. The search-first approach means existing clients are matched to their record rather than creating a second entry. If you skip the search and go straight to the add form for someone who already exists, you will end up with two separate records for the same person.

Always search first.
