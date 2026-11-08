---
id: REQ-HTCCSRT
type: software-requirement
title: Device registry detects safety limits
status: Draft
owner: H. Mostafa
tags:
  - cost
  - customer-request
former-id: SW-3AV07M
parent: REQ-NGQ979G
order: a0
links:
  - type: refines
    target: REQ-NGQ979G
    confirmed: 3805c8343c55
---
The device registry shall switch the operating mode at least once per minute.

**Rationale:** Safety limits must stay consistent for the user below 0.5 W in standby.
