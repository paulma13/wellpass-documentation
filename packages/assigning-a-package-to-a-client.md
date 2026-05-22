---
title: Assigning a package to a client
audience: staff-web users
app: staff-web
category: packages
last_updated: 2026-05-22
---

# Assigning a package to a client

## Overview

Use this when you want to give a package to a specific client — whether they paid in cash, received a discount, or earned a complimentary bundle. You can assign a package to any client: existing studio clients, new clients who are not yet in your system, and clients who use the Wellpass app. The assignment flow handles all three cases.

The **Assign to client** icon is available on any active package row in the Packages tab. The icon is disabled for inactive packages.

## How to assign a package

### Step 1 — Find or add the client

1. Go to the **Packages** page in the left sidebar.
2. Click the **Packages** tab.
3. On the package you want to assign, click the **Assign to client** icon (the person+ icon on the right side of the row).
4. The assignment modal opens, showing the package name at the top.
5. Search for the client by name. If the client appears in the results, click their name to select them and then click **Confirm**.
6. If the client is not found, click **Did not find the client?** to add them. Fill in their first name, last name, phone number (required), and optionally their email address.
7. After entering the client's phone number, the system checks whether that number matches an existing Wellpass account. If a match is found, you see: "Wellpass user found on app: [first name] — is this correct?" Confirm if correct, or go back to enter a different number.
8. Once the client is confirmed, the flow moves to the next step.

### Step 2 — Duplicate warning (if applicable)

If the client you selected already has an active copy of this same package, you see a warning before continuing:

"[Name] already has an active [package name] with [X] sessions remaining, expiring on [date]. Do you still want to assign another one?"

You can click **Cancel** to stop, or **Yes, Proceed** to continue assigning a second copy. Assigning the same package twice is allowed — the duplicate warning is informational, not a block.

### Step 3 — Confirm the assignment

Review the assignment details before confirming:

- **Client** — the client you selected.
- **Sessions** — the number of sessions included in the package.
- **Standard price** — the package's default price.
- **Price paid** — editable. Defaults to the package's standard price. Change this if the client paid a different amount (higher or lower).
- **Free button** — clicking **Free** sets the price to $0 and disables the price field. Clicking **Undo Free** restores the standard price.
- **Reason for price change** — this field appears and becomes required whenever the price paid differs from the standard price, in any direction (lower, higher, or free). Enter a short note explaining the reason — for example, "First-time client discount" or "Staff comp."

Click **Confirm** to complete the assignment. The package is added to the client's account immediately.

To go back and select a different client, click **Back**.

## Settings and options

### Price paid

The price you enter is recorded with the assignment and appears in your package history and reports. It does not affect the number of sessions or the validity period of the package. You can enter any amount, including zero using the Free button.

### Reason for price change

This field is only shown when the price paid is different from the standard price. It is required in that case. The reason is stored with the assignment and is visible when you view the client list for a package, making it easy to audit discounts or special pricing decisions later.

### Payment method

The payment method recorded depends on how you complete the assignment. If the **Free** button is active when you confirm, the payment method is recorded as **Free**. Otherwise it is recorded as **Cash**.

## Edge cases

- If the package is inactive, the Assign to client icon is disabled. Reactivate the package first before assigning it.
- You can assign the same package to a client more than once. The duplicate warning will appear, but it does not prevent you from proceeding.
- If the price paid differs from the standard price — even if only by a small amount — the reason field is required. You cannot confirm the assignment without entering a reason.
- New clients added through this flow are created in your studio's client list immediately. If their phone number matched a Wellpass account, they are linked to that account.
