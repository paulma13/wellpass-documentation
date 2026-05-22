---
title: Creating a package
audience: staff-web users
app: staff-web
category: packages
last_updated: 2026-05-22
---

# Creating a package

## Overview

Create a package template when you want to offer a session bundle to clients — for example, a 10-class bundle for $100. Once created, the package is immediately available for your staff to assign to clients or, if you make it public, for clients to purchase themselves through the Wellpass app.

Receptionists cannot create packages.

## How to create a package

1. Go to the **Packages** page in the left sidebar.
2. Click **New Package** in the top right.
3. The package form opens. Fill in the fields as described below.
4. Click **Create** to save.

The package appears in the Packages table immediately and is active by default.

## Fields

### Package name

Required. This is the name shown to clients in the Wellpass app and to staff throughout the app. Choose a name that clearly describes the bundle — for example, "10-Class Pack" or "Monthly Unlimited."

### Description

Optional. A longer description visible to clients in the Wellpass app when they browse packages. Use this to explain what the package includes, any restrictions, or any other details a client would want to know before purchasing.

### Sessions

Required. The number of sessions included in the package. Must be at least 1. Defaults to **10**.

### Price

Required. The standard price charged when this package is assigned or purchased. Defaults to **$100**.

To offer the package at no charge, switch on the **Free** toggle next to the price field. When Free is on, the price is set to $0 and the price field is disabled. Note that a free package cannot be set to public — see the visibility section below for details.

### Validity

How many days the package remains valid after it is assigned or purchased. Defaults to **30 days**. The description under the field reads: "How many days after purchase until the package expires."

To create a package with no expiry date, switch on the **No expiry** toggle. When No expiry is on, the days field is disabled and the package never expires regardless of when it was assigned.

If you enter a specific number of days, it must be at least 1.

### Valid for

This field only appears when your studio offers both classes and appointments. Use the checkboxes to choose which services the package can be used for: **Classes**, **Appointments**, or both. At least one must be checked.

If your studio offers only classes or only appointments, this field is not shown and the package automatically applies to your studio's service type.

### Which classes can this package be used for?

This field only appears when **Classes** is checked in the Valid for field.

Choose one of two options:

- **All classes** — the package can be used for any class in your studio's schedule.
- **Specific classes** — the package can only be used for certain classes. When you select this option, a searchable list appears where you can select the individual class names this package applies to. At least one class must be selected.

### Visibility

Controls whether clients can see and purchase this package in the Wellpass app, or whether it is only available through staff assignment. Defaults to **Public**.

- **Public — visible to all clients in the app** — the package appears in the Wellpass app for clients to browse and buy themselves.
- **Private — only assignable by staff** — the package is hidden from clients. Only your staff can assign it manually.

## Public vs private and active vs inactive

These are two independent settings that work differently, and it is important to understand both.

**Visibility (public vs private)** controls who can discover and purchase the package.

- Public: the package is visible in the Wellpass app. Clients can find it and buy it themselves.
- Private: the package is invisible to clients. Only staff can assign it from the Packages page.

**Status (active vs inactive)** controls whether the package is currently operational.

- Active: the package can be newly assigned to clients. If it is also public, it appears in the Wellpass app.
- Inactive: the package cannot be newly assigned to anyone. If it was public, it disappears from the app. Clients who already own a copy are not affected.

These settings combine independently. A few common examples:

- **Public + Active** — visible in the app and assignable by staff. This is the standard state for packages you are currently selling.
- **Private + Active** — not visible in the app, but staff can still assign it manually. Use this for staff-controlled offers.
- **Public + Inactive** — no longer visible in the app and cannot be assigned. Use this to retire a package without deleting it.
- **Private + Inactive** — fully retired. Not visible anywhere and cannot be assigned.

## The free package rule

A free package cannot be set to public. If you set a package to Free and also set the visibility to Public, the form shows a red alert: "A free package cannot be public — anyone would be able to claim it without paying. Set a price or switch it to Private to continue." The Create button is disabled until you resolve this by either adding a price or switching the visibility to Private.

## Default values

When you open the New Package form, it is pre-filled with these defaults:

- Sessions: 10
- Price: $100
- Validity: 30 days
- Visibility: Public
- Classes: checked (if your studio offers classes)
- Appointments: checked only if your studio does not offer classes
