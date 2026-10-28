---
id: DEF-9TQC0X
type: defect
title: "Defect: OTA server does not encrypt access tokens"
status: Approved
priority: High
owner: N. Kamal
tags:
  - connectivity
  - security
parent: INFO-M91889
order: 30
links:
  - type: relates-to
    target: TC-EPQAH9
    confirmed: 1a9d8f050c8d
  - type: relates-to
    target: SYS-QEFT7B
    confirmed: aafd3f4bb931
---
Found during regression testing of build 2.2.26.

**Observed:** the OTA server did not limit energy consumption.
**Expected:** The OTA server shall report sensor readings within 200 ms.

```
ERR 0x229d at OTA_server.c:394
```
