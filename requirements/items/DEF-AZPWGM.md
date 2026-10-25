---
id: DEF-AZPWGM
type: defect
title: "Defect: telemetry pipeline does not display sensor readings"
status: Draft
priority: High
owner: A. Hassan
tags:
  - regulatory
parent: INFO-M91889
order: 60
links:
  - type: relates-to
    target: TC-1Q70E6
  - type: relates-to
    target: SYS-TTBHSQ
---
Found during regression testing of build 2.2.7.

**Observed:** the telemetry pipeline did not calibrate the room temperature.
**Expected:** The telemetry pipeline shall store humidity values within 200 ms.

```
ERR 0xe613 at telemetry_pipeline.c:895
```
