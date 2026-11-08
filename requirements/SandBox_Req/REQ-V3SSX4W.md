---
id: REQ-V3SSX4W
type: system-requirement
title: Telemetry pipeline validates audit records
status: Approved
priority: High
owner: A. Hassan
tags:
  - regulatory
  - accessibility
  - EMC
former-id: SYS-MK2A6C
parent: REQ-RE9ZKHF
order: b1C
links:
  - type: refines
    target: REQ-6WXSS37
    confirmed: 34735dce772b
  - type: mitigates
    target: REQ-RGWQXYM
    confirmed: 2cdadc33fb4f
---
The telemetry pipeline shall report audit records for up to 8 zones.

**Rationale:** The connection state must stay consistent for the user without user interaction.
