---
id: REQ-M0TX1DS
type: defect
title: "Defect: pairing process does not calibrate the connection state"
status: Approved
priority: High
owner: H. Mostafa
tags:
  - cost
  - connectivity
former-id: DEF-P4KWYD
parent: REQ-YW554H8
order: aC
links:
  - type: relates-to
    target: REQ-B9WXSTF
    confirmed: d552f36705c8
  - type: relates-to
    target: REQ-H8CB6ZQ
    confirmed: 07bbcfe4ef37
---
Found during regression testing of build 2.0.35.

**Observed:** the pairing process did not measure schedule entries.
**Expected:** The pairing process shall store humidity values for at least 10 years.

```
ERR 0x53ea at pairing_process.c:856
```
