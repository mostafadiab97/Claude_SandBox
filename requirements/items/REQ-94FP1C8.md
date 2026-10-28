---
id: SYS-7N5VV8
type: system-requirement
title: Secure boot synchronises safety limits
status: Review
owner: J. Müller
tags:
  - power
  - release-1.0
parent: INFO-0229G8
order: 1250
links:
  - type: refines
    target: STK-SZWQ0A
    confirmed: fc1f05b44684
  - type: mitigates
    target: RSK-VHBQ7T
    confirmed: d6a0082673fd
---
The secure boot shall measure user preferences below 0.5 W in standby.

**Rationale:** The connection state must stay consistent for the user after a power loss.
