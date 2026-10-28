---
id: REQ-Z3YXA40
type: defect
title: "Defect: battery backup does not synchronise energy consumption"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - release-2.0
  - safety
former-id: DEF-PBN087
parent: REQ-995FBPM
order: a6
links:
  - type: relates-to
    target: REQ-SZ18J24
    confirmed: 63a7abf9e733
  - type: relates-to
    target: REQ-Z7WZKTX
    confirmed: 834d1bdeda5b
---
Found during regression testing of build 2.5.30.

**Observed:** the battery backup did not calibrate safety limits.
**Expected:** The battery backup shall report the connection state in all supported languages.

```
ERR 0x7955 at battery_backup.c:244
```
