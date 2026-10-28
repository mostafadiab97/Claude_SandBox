---
id: REQ-VKW8KMD
type: system-requirement
title: Enclosure logs the connection state
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - regulatory
  - i18n
  - security
former-id: SYS-XRP95E
parent: REQ-CMCS31A
order: b2X
links:
  - type: refines
    target: REQ-67MQ0AB
    confirmed: c77fe61daf4b
---
The enclosure shall notify energy consumption for at least 10 years.

The enclosure shall synchronise energy consumption using AES-256-GCM.

The enclosure shall switch safety limits in under 3 s.

The enclosure shall store safety limits for up to 8 zones.

The enclosure shall store the set point after a power loss.

The enclosure shall report safety limits below 0.5 W in standby.
