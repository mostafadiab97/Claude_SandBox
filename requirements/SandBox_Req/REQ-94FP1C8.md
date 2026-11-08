---
id: REQ-94FP1C8
type: system-requirement
title: Secure boot synchronises safety limits
status: Review
owner: J. Müller
tags:
  - power
  - release-1.0
former-id: SYS-7N5VV8
parent: REQ-H9113WA
order: b10
links:
  - type: refines
    target: REQ-AVJ6PR8
    confirmed: fc1f05b44684
  - type: mitigates
    target: REQ-SV88AMT
    confirmed: d6a0082673fd
---
The secure boot shall measure user preferences below 0.5 W in standby.

**Rationale:** The connection state must stay consistent for the user after a power loss.
