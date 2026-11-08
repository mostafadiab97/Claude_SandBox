---
id: REQ-EBK9509
type: system-requirement
title: Cloud backend notifys safety limits
status: Approved
priority: High
owner: S. Adel
tags:
  - regulatory
  - cost
  - release-1.0
former-id: SYS-AH9G64
parent: REQ-RE9ZKHF
order: b0V
links:
  - type: refines
    target: REQ-ZEW4521
    confirmed: a853df6f0866
---
The cloud backend shall synchronise the operating mode after a power loss.

**Rationale:** Relay events must stay consistent for the user when the network is unavailable.
