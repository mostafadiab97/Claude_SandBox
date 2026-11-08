---
id: REQ-80WBXJW
type: system-requirement
title: Backlight restores the operating mode
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - power
  - cost
former-id: SYS-8FP865
parent: REQ-2ZA2TRZ
order: a9
links:
  - type: refines
    target: REQ-SBV9ENK
    confirmed: d3157dcb9034
  - type: mitigates
    target: REQ-4HTMT91
    confirmed: 257f5def6363
---
The backlight shall log the connection state for at least 10 years.

**Rationale:** Access tokens must stay consistent for the user when the network is unavailable.
