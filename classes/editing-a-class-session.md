---
title: How to edit a class session
audience: staff-web users
app: staff-web
category: classes
last_updated: 2026-05-10
--- 


# How to edit a class session

## Overview

You can edit a class session in two ways: edit a single session from the calendar, or bulk-edit multiple sessions from the Classes page. Single-session editing lets you change one specific occurrence. Bulk editing lets you change a range of sessions for a class at once, with optional filters to narrow which sessions are affected.

Changes you make to a session do not affect the class template or any other sessions. When a session is saved, clients who have booked it receive a push notification informing them the session has been updated.



## How to edit a single session

1. Go to **Calendar** in the left sidebar.
2. Click the session card for the session you want to edit.
3. In the session detail panel that opens, click **Edit** (pencil icon) in the panel header.
4. The **Edit Session** modal opens, pre-filled with the session's current values.
5. Change any of the fields you want to update (see [Settings and options](#settings-and-options) below).
6. Click **Save Changes**.

The **Save Changes** button is only active when at least one field has been changed from its current value. Clearing a field back to empty does not count as a change — the original value is kept.



## How to bulk-edit sessions

Bulk editing applies the same changes to multiple sessions of a class across a date range.

### Open the bulk edit modal

You can open bulk editing in two ways:

- From the **Classes** page: click **Bulk Edit Sessions** in the top-right corner. You then select a class manually inside the modal.
- From a class card on the **Classes** page: click the **Bulk Edit Sessions** button on the card. The modal opens with that class pre-selected.

### Step 1 — Set the scope

Inside the **Bulk Edit Sessions** modal:

1. Select a **Class** from the dropdown (if not pre-selected).
2. Select a **Branch**.
3. Set a **Date from** (required). Set a **Date to** if you want an end date; leave it blank to include all future sessions.

Once all three required fields are filled, the modal loads the available filter options for that scope.

### Step 2 — Narrow the sessions (optional)

Use the filter chips to narrow which sessions are affected:

- **Day of week** — select one or more days (Sun, Mon, Tue, …). Selecting days also narrows the available start time chips.
- **Start time** — select one or more start times from the chips shown.
- **Instructor** — select a specific instructor from the dropdown.

The modal shows a live count of how many sessions match your current filters. Click **View Sessions** to open a side panel listing each affected session by date, time, and instructors.

### Step 3 — Choose what to change

Under **Fields to change (leave blank to keep unchanged)**, fill in only the fields you want to update. Fields you leave blank are not changed on any session.

A summary at the bottom of the modal confirms which fields you are changing and how many sessions will be affected.

### Step 4 — Save

Click **Save Changes (N sessions)** to apply the changes. The button label shows the number of sessions that will be updated.



## Settings and options

The following fields can be edited on both a single session and in bulk:

| Field | Description |
|||
| **Start time** | The time the session begins. Changing the start time automatically advances the end time by the class's default duration. |
| **End time** | The time the session ends. A warning appears if the duration differs from the class default. |
| **Max capacity** | The maximum number of bookings allowed. A warning appears if you set this below the current number of confirmed bookings. |
| **Price** | The price for this session. This overrides the class-level default price for this session only. |
| **Gender** | Restricts who can book: **Any**, **Male only**, or **Female only**. |
| **Instructor(s)** | One or more instructors assigned to the session. This field is optional — a session can have no assigned instructors. |



## Edge cases

**Capacity below current bookings.** If you lower max capacity below the number of existing confirmed bookings, the system saves the change and shows a warning. Existing bookings are not automatically cancelled — you would need to cancel them manually if required.

**End time differs from class duration.** If the start and end time you set produce a duration different from the class template's default, a warning appears next to the end time field. You can still save the session with a custom duration.

**No fields changed.** In single-session editing, the **Save Changes** button remains disabled until at least one field is different from the session's current value. In bulk editing, at least one field must be filled in before you can save.

**No matching sessions.** In bulk editing, if your date range and filters produce zero matching sessions, the **Save Changes** button is disabled and no action is taken.

**Notifications.** When a session is saved, clients with confirmed bookings receive a push notification: "Your class at [studio name] has been updated…" Instructors assigned to the session also receive a notification on the staff mobile app.