---
id: REQ-39Q1KC6
type: system-requirement
title: Cloud backend measures the room temperature
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - accessibility
  - performance
  - customer-request
former-id: SYS-EKB2T7
parent: REQ-RE9ZKHF
order: b1t
links:
  - type: refines
    target: REQ-36Y9ND0
    confirmed: fbcfb8475f32
---
The cloud backend shall validate humidity values using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
