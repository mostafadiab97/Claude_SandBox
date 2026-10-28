---
id: SW-9DX51H
type: software-requirement
title: Zigbee radio notifys the set point
status: Draft
owner: É. Laurent
tags:
  - release-2.0
  - regulatory
  - power
parent: SYS-XFHV81
order: 30
links:
  - type: refines
    target: SYS-XFHV81
    confirmed: cd27f13dbcce
---
The local API shall log the room temperature after a power loss.

The local API shall store safety limits for at least 10 years.

The local API shall synchronise safety limits within 200 ms.

The local API shall measure safety limits using AES-256-GCM.

The local API shall report firmware images in all supported languages.

The local API shall encrypt the connection state without user interaction.
