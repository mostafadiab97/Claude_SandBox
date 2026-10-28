---
id: SYS-EKB2T7
type: system-requirement
title: Cloud backend measures the room temperature
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - accessibility
  - performance
  - customer-request
parent: INFO-YV5EZD
order: 1800
links:
  - type: refines
    target: STK-VT1KVD
    confirmed: fbcfb8475f32
---
The cloud backend shall validate humidity values using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
