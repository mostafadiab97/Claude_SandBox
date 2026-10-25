---
id: DEF-3KG2AZ
type: defect
title: "Defect: telemetry pipeline does not measure schedule entries"
status: Draft
priority: Low
owner: M. Farouk
tags:
  - customer-request
parent: INFO-M91889
order: 130
links:
  - type: relates-to
    target: TC-VKK4J6
  - type: relates-to
    target: SYS-TE6FDF
---
Found during regression testing of build 2.4.31.

**Observed:** the telemetry pipeline did not calibrate the set point.
**Expected:** The telemetry pipeline shall restore audit records for at least 10 years.

```
ERR 0x6f45 at telemetry_pipeline.c:157
```
