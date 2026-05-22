---
title: Editing a package
audience: staff-web users
app: staff-web
category: packages
last_updated: 2026-05-22
---

# Editing a package

## Overview

Edit a package template when you need to update its name, price, sessions, validity, visibility, or the services it covers. You can edit a package at any time — whether it is active or inactive.

Receptionists cannot edit packages.

## How to edit a package

1. Go to the **Packages** page in the left sidebar.
2. Click the **Packages** tab.
3. Click anywhere on the package row you want to edit. This opens the edit modal.
4. Make your changes to any of the fields.
5. Click **Save** to apply the changes.

## What changes after saving

Changes to a package template take effect immediately for future assignments. If a client purchases or is assigned the package after you save, they receive the updated sessions count, price, and validity.

**Existing client packages are not retroactively changed.** If a client already owns a copy of the package, their copy keeps the session count and expiry date it had when it was originally assigned. Any price they paid is also unchanged. Editing a template never removes sessions from a client who already has them.

## The class scope narrowing warning

If you reduce the class scope of a package that already has active owners, the app shows a confirmation before saving.

This warning appears when:

- The package previously covered **All classes** and you switch it to **Specific classes** with a smaller selection, or
- The package was already set to Specific classes and you remove one or more classes from the list.

The confirmation modal shows:

- Title: "Reduce class scope?"
- A message stating how many clients currently own this package and explaining that their existing packages will no longer be usable for the removed classes.
- Two buttons: **Cancel** and **Continue anyway**.

Clicking **Continue anyway** saves the change. Clients who already own the package will find that their sessions can no longer be used for the classes you removed. Their remaining session count does not change, but their usable services are narrowed.

If you click **Cancel**, the change is not saved and the package remains as it was.

## Edge cases

- If you change a package's **Valid for** setting (for example, removing Appointments coverage), clients who already own the package and have not yet used their sessions may find their package no longer works for the removed service type.
- Changing the **price** on a template does not affect what clients already paid — it only changes the default price shown when assigning the package to future clients.
- Switching visibility from **Public** to **Private** immediately removes the package from the Wellpass app. Clients who already purchased it are not affected.
- You cannot save a package that is set to both **Free** and **Public**. If you change a package to Free, you must also switch it to Private before saving.
