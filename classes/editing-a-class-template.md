---
title: How to edit a class template
audience: studio_owner
app: staff-web
category: classes
last_updated: 2026-05-10
---

# How to edit a class template

## Overview

A class template is the master record for a class — it holds the default name, type, description, duration, capacity, price, gender restriction, cancellation window, cover image, and active status. Editing a template updates only those defaults. It does not change any sessions that have already been scheduled, including upcoming ones. If you need to change scheduled sessions, use the Bulk Edit Sessions feature instead.

## How to edit a class template

1. In the left sidebar, go to **Classes**.
2. Find the class card you want to edit. Inactive classes appear faded but are still editable.
3. Click anywhere on the card. The **Edit Class Template** modal opens, pre-filled with the current values.
4. Update any of the fields you want to change (see Settings and options below).
5. Click **Save Changes**.

The modal closes and the class list refreshes to show the updated details.

## What changes and what doesn't

This is the most important thing to understand when editing a class template.

**What changes:** The template record itself. The updated values become the new defaults for that class. Any new sessions you schedule after saving will use the updated defaults.

**What does not change:** Any sessions that already exist — including sessions scheduled in the future. Changing the template's default capacity, price, duration, gender restriction, or any other field has no effect on sessions that have already been created. Clients with existing bookings are not affected in any way.

To update sessions that are already scheduled, use the **Bulk Edit Sessions** button on the class card. To update a single already-scheduled session, open it from the **Calendar** and use the session edit form.

## Settings and options

- **Class name** — the name shown to clients when browsing and booking. Required.
- **Type** — the category the class belongs to (for example, Pilates Reformer or Yoga). Required.
- **Description** — optional text shown to clients on the class detail screen.
- **Duration (minutes)** — the default length of a session. Required.
- **Max capacity** — the default maximum number of spots per session. Required.
- **Price** — the default price per session. Individual sessions can override this.
- **Gender** — restricts who can book: Any, Male only, or Female only.
- **Cancellation window (hours)** — how many hours before a session a client can cancel. Set to 0 to allow cancellation right up until the session starts.
- **Active** — when on, the class is visible and bookable by clients. When off, the class is hidden. Toggling this does not affect existing sessions or bookings.
- **Cover image** — an optional image displayed on the class card.

## Edge cases

**Deactivating a class:** Setting **Active** to off hides the class from clients going forward. Sessions that are already scheduled remain active and bookable unless you cancel them individually.

**Changing the price:** Updating the template price does not reprice any existing sessions. Sessions created before the edit keep their original price. New sessions scheduled after the edit will use the updated default, which can still be overridden at the session level.

**Changing duration:** The new duration applies only to new sessions. Existing sessions keep their original start and end times.

**Inactive class with active sessions:** A class can be inactive (hidden from clients) while still having upcoming sessions. Clients who already have bookings for those sessions are not affected.

## Related

- [Classes and sessions — what's the difference](classes-vs-sessions.md)
- [Creating class sessions](creating-class-sessions.md)
- [Editing a class session](editing-a-class-session.md)
- [Bulk editing class sessions](bulk-editing-class-sessions.md)
