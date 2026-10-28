---
id: REQ-RQVMA64
type: defect
title: "Defect: telemetry pipeline does not display sensor readings"
status: Draft
priority: High
owner: A. Hassan
tags:
  - regulatory
former-id: DEF-AZPWGM
parent: REQ-9FNWH0D
order: a5
links:
  - type: relates-to
    target: REQ-EPH41XC
    confirmed: 1dc21fb619a5
  - type: relates-to
    target: REQ-YY33AAD
    confirmed: ac320e4fa404
---
Found during regression testing of build 2.2.7.

**Observed:** the telemetry pipeline did not calibrate the room temperature.
**Expected:** The telemetry pipeline shall store humidity values within 200 ms.

```
ERR 0xe613 at telemetry_pipeline.c:895
```
