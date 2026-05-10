---
title: How to bulk edit class sessions
audience: staff-web users
app: staff-web
category: classes
last_updated: 2026-05-10
---

# How to bulk edit class sessions

## Overview

Bulk editing lets you update multiple sessions of the same class at once across a date range. Instead of opening each session individually, you define a scope — class, branch, and date range — then optionally narrow it down by day of the week, start time, or instructor. Only the fields you fill in are changed; fields you leave blank stay exactly as they are.

You can also use the same workflow to cancel a group of sessions in bulk. Cancelling sessions is a separate action from editing them and requires an extra confirmation step.



## How to bulk edit class sessions

### Step 1 — Open the bulk edit modal

Go to **Classes** in the left navigation. You can open the bulk edit modal in two ways:

- Click **Bulk Edit Sessions** at the top right of the Classes page to start without a pre-selected class.
- Click **Bulk Edit Sessions** on a specific class card to start with that class already selected.

### Step 2 — Select the class, branch, and date range

At the top of the modal, fill in three required fields:

| Field | Notes |
|||
| **Class** | The class template whose sessions you want to edit. If you opened from a class card, this is pre-filled. |
| **Branch** | The branch where the sessions are scheduled. |
| **From** | The start date of the range. Defaults to today. |
| **To (optional)** | The end date of the range. Leave blank to include all sessions from the start date onward with no cutoff. |

Once all three required fields are set, the modal loads the available filter options for that scope.

### Step 3 — Narrow sessions (optional)

After the scope is set, a **Narrow sessions** panel appears showing which sessions fall in the selected range. Use these optional filters to target a subset:

- **Day of week** — Select one or more days (for example, Mon and Wed) to limit changes to sessions on those days only. Days that have no sessions in the range are not shown.
- **Start time** — Select one or more start times. If you have days selected, only the start times that exist on those days are shown.
- **Instructor** — Select a specific instructor to limit changes to sessions that include that person.

All filters work together. For example: Mondays + 9:00 AM + a specific instructor means only Monday 9 AM sessions led by that instructor are affected.

A live count shows how many sessions will be affected. As you adjust the filters, the count updates automatically.

> If you select no filters at all, every session in the date range is affected.

### Step 4 — Review the session list (optional)

If the affected count is greater than zero, a **View Sessions** button appears. Click it to open a side panel listing every session that will be changed, with its date, time, and instructors. This is a preview only — nothing is changed until you save.

The panel closes automatically if you change any filter or scope setting, because the list would be out of date.

### Step 5 — Fill in the fields to change

Below the filter panel, fill in only the fields you want to update. Any field left blank is ignored — the existing value on each session is kept.

| Field | Behavior when filled in |
|||
| **Start time** | Updates the start time on all affected sessions. When you set a start time, the end time is automatically calculated using the class's default duration. |
| **End time** | You can adjust the end time independently. A warning appears if the resulting duration differs from the class's default. |
| **Max capacity** | Sets the maximum number of bookable spots on all affected sessions. |
| **Price** | Sets the per-session price, overriding the class default for these sessions. |
| **Gender** | Sets the gender restriction: Any, Male only, or Female only. |
| **Instructor(s)** | Replaces the instructor list on all affected sessions. Selecting one or more instructors replaces whoever was assigned. To clear all instructors, select at least one and then remove them — the field must be touched to register a change. |

### Step 6 — Review the confirmation summary

Once you have filled in at least one field and the affected count is greater than zero, a summary bar appears beneath the fields. It lists every field you have touched and the number of sessions that will be changed. Review this before proceeding.

### Step 7 — Save

Click **Save Changes**. The button label includes the session count (for example, "Save Changes (12 sessions)") so you can confirm the scope at a glance. The modal closes automatically when the save completes.



## Settings and options

### Fields explained

**Start time and end time**
These are session-level values. Setting them here does not change the class template's default duration — only these specific sessions are updated. A warning icon appears next to the end time field if the gap between start and end differs from the class's default duration.

**Price**
Sessions have their own price field that overrides the class default. Setting a price here writes it at the session level. If you want sessions to fall back to the class default price, edit each session individually and clear the price field.

**Instructor(s)**
Updating instructors replaces the entire instructor list on every affected session — it is not additive. If you want to add one instructor while keeping others, you need to edit sessions individually.

**Gender**
Options are Any, Male only, or Female only. This setting restricts which clients can book the session.

### Permission requirement

Only users with the **Owner** or **Manager** role can bulk edit or bulk cancel sessions.



## Edge cases

**No sessions found in the range**
If the class has no sessions matching the selected class, branch, and date range, the filter panel does not appear and the save button remains disabled. Check that the branch and date range are correct and that sessions exist in that period.

**Filters that produce zero matches**
If your combination of day, time, and instructor filters results in zero matching sessions, the save button is disabled and "0 sessions will be affected" is shown. Adjust the filters to widen the scope.

**Changing instructors removes existing assignments**
Instructors on the affected sessions are fully replaced, not merged. If sessions have different instructor assignments and you use bulk edit to set instructors, all sessions will end up with the same instructor list you selected.

**Date range with no upper bound**
Leaving the **To** date blank applies the edit to all future sessions from the start date onward — including sessions you may not yet know exist. Confirm the affected count before saving.



## Cancelling sessions in bulk

The bulk edit modal also lets you cancel all sessions matching the current scope and filters.

### How to cancel sessions in bulk

1. Set up the scope and filters as described above until the affected count shows the correct number of sessions.
2. Click **Cancel Sessions** (bottom left of the modal).
3. A confirmation panel appears showing the number of sessions that will be cancelled and a warning that all confirmed bookings will be cancelled and packages refunded. If any sessions have clients who paid by card online, the count of card payments that will be refunded is also shown.
4. Click **Yes, cancel N sessions** to confirm, or **Go back** to return without cancelling.

Cancelling sessions is permanent and cannot be undone from the app.

**What happens when sessions are cancelled:**
- Each session is marked inactive and no longer appears to clients.
- All confirmed bookings for those sessions are cancelled.
- Clients who used a package to book have their session credit returned to their package automatically.
- Clients who paid by card online receive a refund.
- Clients on the waitlist for those sessions have their waitlist entries cancelled.
- Clients with a booking or waitlist entry receive a push notification that the session has been cancelled. Walk-in clients who have no account do not receive a notification.



## Related

- [How to edit a single class session](editing-a-class-session.md)
- [How to create class sessions](creating-class-sessions.md)
- [How to cancel a single class session](editing-a-class-session.md)
