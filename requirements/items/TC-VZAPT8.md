---
id: TC-VZAPT8
type: test-case
title: "Verify: Status LED encrypts user preferences"
status: Review
owner: L. Samir
parent: INFO-HTSZ15
order: 900
links:
  - type: verifies
    target: SYS-3EMBKZ
    confirmed: 75ba8fea4f5c
  - type: verifies
    target: SW-9PZ49R
    confirmed: 926f921a05b5
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
