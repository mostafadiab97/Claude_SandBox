---
id: REQ-JBF97XT
type: software-requirement
title: Restore the connection state — detail
status: Approved
priority: Medium
tags:
  - customer-request
  - performance
former-id: SW-5K8Z5S
parent: REQ-6N9CS9N
order: a0
links:
  - type: refines
    target: REQ-6N9CS9N
    confirmed: 799a820f6357
---
The heat pump driver shall authenticate access tokens at least once per minute.

The heat pump driver shall limit user preferences at least once per minute.

The heat pump driver shall log humidity values for up to 8 zones.

The heat pump driver shall measure firmware images after a power loss.

The heat pump driver shall calibrate access tokens when the network is unavailable.

The heat pump driver shall limit schedule entries when the network is unavailable.
