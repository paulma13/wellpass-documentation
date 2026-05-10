---
title: How to cancel a class session
audience: staff-web users
app: staff-web
category: classes
last_updated: 2026-05-10
---

# How to cancel a class session

## Overview

Cancelling a class session removes it from the schedule and cancels every active booking attached to it. All clients who are booked or on the waitlist receive an in-app push notification. Package sessions consumed by those bookings are automatically returned to each client's package. If any clients paid by card online, you can optionally process their refunds at the same time. The action cannot be undone.



## How to cancel a class session

1. Open the **Calendar** from the main navigation.
2. Find the session you want to cancel and click its card to open the session detail panel.
3. In the detail panel, scroll to the bottom and click the **Cancel class** button. A confirmation dialog opens.
4. Review the summary. The dialog shows:
   - The class name and total number of active bookings.
   - How many bookings were paid by card online (if any). A **Refund online card payment(s)** toggle appears for these.
   - A note that package sessions will be returned automatically.
5. If there are online card bookings, decide whether to issue refunds. The toggle is off by default — turn it on to process refunds for those clients.
6. Read the **"This cannot be undone"** warning, then click **Yes, Cancel Class**.
7. The dialog shows the outcome:
   - How many card refunds succeeded (if you chose to refund).
   - How many card refunds failed, if any.
8. Click **Close**. The calendar refreshes and the session no longer appears.



## Settings and options

### Refund online card payments

When a session has bookings that were paid by card online, the cancellation dialog shows a **Refund online card payment(s)** toggle. It is off by default.

- **Toggle off (default):** The bookings are cancelled but no card refund is sent. Use this if the client has already been refunded outside the system or if you do not want to issue a refund.
- **Toggle on:** The system attempts to refund each card payment through the payment gateway before cancelling. The dialog reports how many refunds succeeded and how many failed after the operation completes.

### Package session returns

If a client booked using a session package, their session is automatically returned to their package when the class is cancelled. This happens regardless of the refund toggle — you do not need to take any additional action. If a package was exhausted when the session was returned, it becomes active again.

### Waitlist entries

All clients on the waitlist with a "waiting" status are also cancelled when the session is cancelled. They receive the same "Class Cancelled" push notification as booked clients.



## Edge cases

### Some card refunds fail

If you turned on the refund toggle and one or more refunds could not be processed, the dialog shows a count of failed refunds after the cancellation completes. The session and all bookings are still cancelled — the failed refund does not block the cancellation. An orange **"Refund not processed — contact Wellpass"** badge appears on each affected booking in the list while the modal is still open. Contact the Wellpass team to resolve those refunds manually.

### Walk-in bookings

Clients who were added as walk-ins without a Wellpass account do not receive a push notification. Their bookings are still cancelled.

### Attended and no-show bookings

Bookings with an "attended" or "no-show" attendance status are included in card refunds when the session is cancelled. Package sessions are not returned for these bookings — only confirmed bookings that have not yet been attended receive a package session refund.

### Session is in the past

You can cancel a past session. The same rules apply — bookings are cancelled, package sessions are returned for confirmed bookings, and card refunds can be optionally issued.

### Error during cancellation

If the cancellation itself fails, the dialog shows: "Failed to cancel class — please contact the Wellpass team." The session is not cancelled. Contact the Wellpass team to investigate.