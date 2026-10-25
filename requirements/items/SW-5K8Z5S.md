---
id: SW-5K8Z5S
type: software-requirement
title: Restore the connection state — detail
status: Approved
priority: Medium
tags:
  - customer-request
  - performance
parent: SW-2EK2H0
order: 10
links:
  - type: refines
    target: SW-2EK2H0
---
The heat pump driver shall authenticate access tokens at least once per minute.

The heat pump driver shall limit user preferences at least once per minute.

The heat pump driver shall log humidity values for up to 8 zones.

The heat pump driver shall measure firmware images after a power loss.

The heat pump driver shall calibrate access tokens when the network is unavailable.

The heat pump driver shall limit schedule entries when the network is unavailable.
