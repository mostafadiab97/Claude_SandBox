---
id: REQ-BCT9EV1
type: test-case
title: "Regression: Enclosure limits firmware images"
status: Draft
priority: Low
owner: A. Hassan
former-id: TC-WRKBG2
parent: REQ-6H15AV2
order: b1m
links:
  - type: verifies
    target: REQ-PEMQFK5
    confirmed: caa88f61d9bd
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
