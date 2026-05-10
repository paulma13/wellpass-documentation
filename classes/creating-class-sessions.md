---
title: How to create a class session
audience: staff-web users
app: staff-web
category: classes
last_updated: 2026-05-10
---

# How to create a class session

## Overview

Class sessions are the individual scheduled occurrences of a class — for example, "Monday Pilates Reformer at 9:00 am on June 2." You create sessions in bulk using a four-step wizard that generates recurring sessions across a date range. Before you can schedule sessions, a class template must already exist.



## How to create a class session

Creating sessions is a two-stage process: first create the class template (if one does not already exist), then use the session wizard to schedule it.

### Stage 1 — Create the class template (if needed)

1. Go to the **Classes** page from the sidebar.
2. Click **Create Class Template** in the top-right corner.
3. Fill in the template fields (see [Settings and options — class template fields](#class-template-fields) below).
4. Click **Create Class Template** to save.

The template now appears in the class list. You can proceed to schedule sessions for it.

### Stage 2 — Schedule sessions using the wizard

1. On the **Classes** page, locate the class card you want to schedule.
2. Click **Schedule Sessions** on the card to open the four-step wizard.
3. Complete each step in order:

#### Step 1 — Branch and dates

1. Select the **Branch** where these sessions will be held.
2. Set a **From** date (today or later) and a **To** date for the schedule period.
3. Click **Next: Time Slots**.

#### Step 2 — Time slots

1. Set a **Start time** and **End time** for the default time slot. When you change the start time, the end time adjusts automatically based on the class duration.
2. Set **Max capacity** — the maximum number of clients who can book this slot.
3. Choose a **Gender** restriction if applicable (Any, Male only, or Female only).
4. Optionally enter a **Price**. Leave this empty to use the class template's default price.
5. Optionally select one or more **Instructor(s)** from the dropdown.
6. To add a second recurring time on the same days (for example, a 9:00 am and an 11:00 am slot), click **Add Time Slot** and fill in the details.
7. Click **Next: Days & Schedule**.

#### Step 3 — Days and schedule

1. Check the box next to each day of the week you want sessions to run (for example, Monday, Wednesday, Friday).
2. By default, every selected day uses the time slot settings from Step 2. To use different times or settings on a specific day, click **Customize** next to that day and update the fields.
3. To revert a customized day back to the default settings, click **Reset** next to that day.
4. Click **Next: Preview**.

#### Step 4 — Preview and confirm

1. Review the full list of sessions that will be created, grouped by day of week. Each row shows the date, time, capacity, price (if set), and instructors.
2. The summary at the top shows the total number of sessions to be created.
3. If anything looks wrong, click **Back** to return to any previous step.
4. Click **Create [N] Sessions** to confirm. The sessions are created and the wizard closes.



## Settings and options

### Class template fields

| Field | Required | Notes |
||||
| Class name | Yes | Displayed to clients when browsing |
| Type | Yes | Category such as Pilates Reformer or Yoga |
| Description | No | Optional text visible to clients |
| Cover image | No | Optional image shown in the client app |
| Duration (minutes) | Yes | Default session length; used to auto-set end times in the wizard |
| Max capacity | Yes | Default maximum spots per session |
| Price | Yes | Default price per session; can be overridden per session |
| Gender | Yes | Any / Male only / Female only |
| Cancellation window (hours) | Yes | How many hours before a session a client can cancel (default 24) |
| Active | Yes | When on, the class is visible and bookable by clients |

### Session wizard fields (Steps 2 and 3)

| Field | Required | Notes |
||||
| Branch | Yes | The studio location for all sessions in this batch |
| From / To dates | Yes | The date range to generate sessions within; start date cannot be in the past |
| Start time | Yes | Session start; changing it auto-adjusts the end time |
| End time | Yes | Session end; a warning appears if the duration differs from the class default |
| Max capacity | Yes | Minimum 1 |
| Gender | No | Defaults to the class template gender |
| Price | No | Leave empty to inherit the class template price |
| Instructor(s) | No | One or more staff members who teach the session |
| Days of week | Yes | At least one day must be selected |
| Per-day customization | No | Overrides the default slot settings for a specific day |



## Edge cases

**Duplicate sessions are skipped silently.** If a session already exists for the same class, date, and start time, the wizard skips that slot rather than creating a duplicate or showing an error. The confirmation count reflects only the newly created sessions.

**No days selected.** If you reach the Preview step without selecting any days in Step 3, the preview shows a "No sessions to create" message and the confirm button shows 0 sessions. Go back and select at least one day.

**Instructor overlap warning.** If two slots in the same step share an instructor and their times overlap, a warning appears next to each affected slot. The warning does not block submission — you must resolve it manually before confirming.

**End time before start time.** The wizard blocks you from advancing to the next step if any slot has an end time equal to or before its start time.

**Classes not enabled.** If your studio does not have the Classes feature enabled, the **Classes** page shows a "Classes not enabled" message instead of the class list. Contact the Wellpass team to enable it.

**Role restriction.** Only users with the **Owner** or **Manager** role can create class templates or schedule sessions. Users with other roles do not see the **Create Class Template** or **Schedule Sessions** controls.



## Related

- [Editing a class session](editing-class-sessions.md)
- [Bulk editing class sessions](bulk-editing-class-sessions.md)
- [Cancelling a class session](cancelling-a-class-session.md)
- [Adding a client to a class](adding-a-client-to-a-class.md)
