---
id: REQ-M5PBBS6
type: system-requirement
title: Cloud backend detects humidity values
status: Draft
priority: Medium
owner: محمد علي
tags:
  - performance
former-id: SYS-9C06SC
parent: REQ-RE9ZKHF
order: b0N
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
  - type: mitigates
    target: REQ-RGWQXYM
    confirmed: 2cdadc33fb4f
---
The cloud backend shall limit humidity values in all supported languages.

**Rationale:** The operating mode must stay consistent for the user with an accuracy of ±0.5 °C.
