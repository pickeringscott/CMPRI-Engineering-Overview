# CMPRI Engineering Overview

CMPRI Engineering is a desktop and mobile workspace for hotel engineering, maintenance, and daily operations. It makes reporting a problem straightforward and gives technicians troubleshooting resources directly within the work order.

This repository provides a public overview, feature information, and release updates. Application source code, operational data, and deployment configuration are maintained privately.

## Easy Work Order Submission

Staff can report a problem in a few steps:

1. Open **Create Work Order**.
2. Select the room or location and describe the problem in plain language—for example, “Room 316 is not cooling.”
3. Add photos, video, or notes if helpful.
4. Submit the request.

The simplified submission flow can infer category and priority from the reported issue. Staff can report a problem without needing to diagnose equipment or choose technical classifications.

Shared-account users enter their name when prompted so the report identifies who submitted it.

## Troubleshooting Guides Within the Work Order

Technicians can open **Suggested Troubleshooting** directly within a work order.

Selecting the associated equipment connects the reported issue with verified documentation for its manufacturer and model, where available. Technicians can access:

- Equipment-specific troubleshooting steps relevant to the reported issue.
- Matching diagnostic and error-code references.
- Verified manufacturer guidance and PDF excerpts.
- Links to original manuals and referenced pages, where available.
- Copy controls for individual troubleshooting steps.

Technicians can record findings and completed work in the work-order notes. Recorded notes help filter out steps already completed.

The work order clearly indicates when an exact verified documentation match is unavailable.

## Other Features

- **Work Order Management:** Assign, track, update, and review maintenance requests.
- **Preventive Maintenance:** Organize scheduled work, inspections, and maintenance history.
- **Locations and Equipment:** Manage rooms, property locations, assets, and documentation.
- **Inventory and Purchasing:** Track supplies, purchase orders, shipments, and receiving.
- **Daily Operations:** Support room operations, pool logs, and staff handoffs.
- **Staff Collaboration:** Share notes, mentions, attachments, and notifications.
- **Role-Based Access:** Provide tools according to each staff member’s permissions.

The desktop interface supports movable windows, with responsive layouts for phones and tablets.

## Latest Release — November 7, 2026

- Improved loading performance through device caching and change-driven refreshes.
- Connected modal colors to a shared palette while preserving their approved appearance.
- Updated Manage Locations with dropdowns and clearer editing controls.
- Corrected scrollbar cursors and standardized mobile button widths.
- Added desktop and mobile Thanksgiving layouts with locally cached artwork and stable animated backgrounds.

## Validation

The release completed automated tests, a production build, and desktop/mobile browser checks.

Live checks verified asset delivery, protected API access, and offline playback of cached seasonal animation.

## Application Access

[Open CMPRI Engineering](https://www.cmpri-engineering.com/)

Application access requires an authorized staff account.

## About This Repository

This repository serves as the public face of CMPRI Engineering, providing project information and release updates while the application’s development repository remains private.
