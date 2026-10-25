---
id: DEF-WQHM9H
type: defect
title: "Defect: pairing process does not authenticate firmware images"
status: Draft
priority: High
owner: K. Tanaka
tags:
  - release-1.0
parent: INFO-Y69DRS
order: 140
links:
  - type: relates-to
    target: TC-P345X4
    confirmed: cd6557aedc8f
  - type: relates-to
    target: SYS-8DZCCC
    confirmed: bfb76bd67963
---
Found during regression testing of build 2.4.1.

**Observed:** the pairing process did not display the room temperature.
**Expected:** The pairing process shall limit safety limits within 200 ms.

```
ERR 0x6935 at pairing_process.c:514
```
