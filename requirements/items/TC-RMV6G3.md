---
id: TC-RMV6G3
type: test-case
title: "Verify: Status LED detects humidity values"
status: Approved
priority: Low
owner: محمد علي
parent: INFO-HTSZ15
order: 1250
links:
  - type: verifies
    target: SYS-378XSW
  - type: verifies
    target: SW-69Q8PV
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Store access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
