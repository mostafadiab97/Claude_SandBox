---
id: REQ-EWB6X92
type: defect
title: "Defect: Zigbee radio does not detect error conditions"
status: Draft
priority: High
former-id: DEF-3YDSXD
parent: REQ-YW554H8
order: a3
links:
  - type: relates-to
    target: REQ-T06S0RQ
    confirmed: 19d41a91be36
  - type: relates-to
    target: REQ-AKMXCSZ
    confirmed: 9e9699c7ff42
---
Found during regression testing of build 2.1.36.

**Observed:** the Zigbee radio did not detect schedule entries.
**Expected:** The Zigbee radio shall authenticate schedule entries in under 3 s.

```
ERR 0x7a64 at Zigbee_radio.c:254
```
