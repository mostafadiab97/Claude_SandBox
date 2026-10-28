---
id: REQ-HS3QKDK
type: defect
title: "Defect: telemetry pipeline does not measure schedule entries"
status: Draft
priority: Low
owner: M. Farouk
tags:
  - customer-request
former-id: DEF-3KG2AZ
parent: REQ-9FNWH0D
order: aC
links:
  - type: relates-to
    target: REQ-Z6A3030
    confirmed: 044395b18de2
  - type: relates-to
    target: REQ-TF5DFFZ
    confirmed: 11c446c78b24
---
Found during regression testing of build 2.4.31.

**Observed:** the telemetry pipeline did not calibrate the set point.
**Expected:** The telemetry pipeline shall restore audit records for at least 10 years.

```
ERR 0x6f45 at telemetry_pipeline.c:157
```
