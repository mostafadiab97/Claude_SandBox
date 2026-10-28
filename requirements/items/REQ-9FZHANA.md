---
id: SYS-2NQ3E8
type: system-requirement
title: OTA server stores the room temperature
status: Review
priority: Low
owner: A. Hassan
tags:
  - release-1.0
  - EMC
parent: INFO-YV5EZD
order: 1930
links:
  - type: refines
    target: STK-R8QH58
    confirmed: 13d6784d2cc9
  - type: mitigates
    target: RSK-HW7CT1
    confirmed: 9979c7ab202d
---
The OTA server shall validate humidity values when the network is unavailable.
