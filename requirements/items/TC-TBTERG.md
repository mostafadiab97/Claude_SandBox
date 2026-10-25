---
id: TC-TBTERG
type: test-case
title: "Verify: Status LED switchs firmware images"
status: Obsolete
owner: محمد علي
parent: INFO-HTSZ15
order: 1240
links:
  - type: verifies
    target: SYS-TYCMRT
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
