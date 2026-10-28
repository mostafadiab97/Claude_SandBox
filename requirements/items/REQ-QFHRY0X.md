---
id: TC-QKQY5N
type: test-case
title: "Verify: Status LED calibrates firmware images"
status: Draft
priority: Low
owner: É. Laurent
tags:
  - ux
parent: INFO-HTSZ15
order: 910
links:
  - type: verifies
    target: SYS-D5BE23
    confirmed: 909e2792e686
  - type: verifies
    target: SW-JQFSRA
    confirmed: 6fff5afcb2fa
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
