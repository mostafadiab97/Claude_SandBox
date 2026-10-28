---
id: REQ-KVCQEKY
type: system-requirement
title: Cloud backend encrypts user preferences
status: Draft
tags:
  - safety
  - cost
  - release-1.0
former-id: SYS-RGPMZF
parent: REQ-RE9ZKHF
order: au
links:
  - type: refines
    target: REQ-6WXSS37
    confirmed: 34735dce772b
---
The cloud backend shall detect the connection state for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly at least once per minute
- No error entries in the device log
