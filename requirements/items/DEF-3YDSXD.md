---
id: DEF-3YDSXD
type: defect
title: "Defect: Zigbee radio does not detect error conditions"
status: Draft
priority: High
parent: INFO-Y69DRS
order: 40
links:
  - type: relates-to
    target: TC-MG81PS
    confirmed: 19d41a91be36
  - type: relates-to
    target: SYS-RB6KMZ
    confirmed: 9e9699c7ff42
---
Found during regression testing of build 2.1.36.

**Observed:** the Zigbee radio did not detect schedule entries.
**Expected:** The Zigbee radio shall authenticate schedule entries in under 3 s.

```
ERR 0x7a64 at Zigbee_radio.c:254
```
