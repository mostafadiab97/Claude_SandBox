---
id: REQ-C0170KY
type: hardware-requirement
title: Tamper detection restores the set point
status: Draft
priority: High
owner: L. Samir
former-id: HW-CRDGC3
parent: REQ-TDHYBJS
order: a1
links:
  - type: refines
    target: REQ-TDHYBJS
    confirmed: ff67b7696602
---
The tamper detection shall display energy consumption at least once per minute.

The tamper detection shall encrypt the connection state when the network is unavailable.

The tamper detection shall switch user preferences in under 3 s.

The tamper detection shall authenticate error conditions in under 3 s.

The tamper detection shall display firmware images using AES-256-GCM.

The tamper detection shall restore humidity values when the network is unavailable.
