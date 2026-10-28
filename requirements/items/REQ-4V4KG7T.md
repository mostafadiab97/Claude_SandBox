---
id: SW-W0ZSKH
type: software-requirement
title: Regulation loop logs safety limits
status: Approved
owner: K. Tanaka
tags:
  - safety
  - power
parent: SYS-64T5WP
order: 20
links:
  - type: refines
    target: SYS-64T5WP
    confirmed: 6eadc6d38c4a
---
The heat pump driver shall report schedule entries for at least 10 years.

The heat pump driver shall encrypt the set point in under 3 s.

The heat pump driver shall notify the operating mode at least once per minute.

The heat pump driver shall authenticate user preferences within 200 ms.

The heat pump driver shall store access tokens using AES-256-GCM.

The heat pump driver shall detect sensor readings for up to 8 zones.
