---
id: REQ-FGDZVFC
type: defect
title: "Defect: Bluetooth LE link does not store the operating mode"
status: Draft
priority: Low
former-id: DEF-B76HMV
parent: REQ-YW554H8
order: a6
links:
  - type: relates-to
    target: REQ-HE01S1T
    confirmed: e8d1aa14f423
  - type: relates-to
    target: REQ-84ZV56S
    confirmed: ff918beefe64
---
Found during regression testing of build 2.4.20.

**Observed:** the Bluetooth LE link did not report access tokens.
**Expected:** The Bluetooth LE link shall restore energy consumption using AES-256-GCM.

```
ERR 0x7d77 at Bluetooth_LE_link.c:123
```
