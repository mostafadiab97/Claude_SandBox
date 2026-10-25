---
id: DEF-1YQGDD
type: defect
title: "Defect: telemetry pipeline does not detect safety limits"
status: Review
priority: Medium
parent: INFO-M91889
order: 10
links:
  - type: relates-to
    target: TC-AD54Z2
  - type: relates-to
    target: SYS-KBPFCV
---
Found during regression testing of build 2.2.38.

**Observed:** the telemetry pipeline did not report user preferences.
**Expected:** The telemetry pipeline shall limit relay events for up to 8 zones.

```
ERR 0xd68f at telemetry_pipeline.c:681
```
