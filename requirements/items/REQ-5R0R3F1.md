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
    confirmed: b9b240fbc5f9
  - type: relates-to
    target: SYS-KBPFCV
    confirmed: 659b9683cc27
---
Found during regression testing of build 2.2.38.

**Observed:** the telemetry pipeline did not report user preferences.
**Expected:** The telemetry pipeline shall limit relay events for up to 8 zones.

```
ERR 0xd68f at telemetry_pipeline.c:681
```
