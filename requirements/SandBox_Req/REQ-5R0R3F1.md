---
id: REQ-5R0R3F1
type: defect
title: "Defect: telemetry pipeline does not detect safety limits"
status: Review
priority: Medium
former-id: DEF-1YQGDD
parent: REQ-9FNWH0D
order: a0
links:
  - type: relates-to
    target: REQ-PT4WE8P
    confirmed: b9b240fbc5f9
  - type: relates-to
    target: REQ-TZ1N94B
    confirmed: 659b9683cc27
---
Found during regression testing of build 2.2.38.

**Observed:** the telemetry pipeline did not report user preferences.
**Expected:** The telemetry pipeline shall limit relay events for up to 8 zones.

```
ERR 0xd68f at telemetry_pipeline.c:681
```
