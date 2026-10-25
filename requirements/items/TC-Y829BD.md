---
id: TC-Y829BD
type: test-case
title: "Verify: Touch display measures sensor readings"
status: Draft
priority: Medium
owner: J. Müller
parent: INFO-HTSZ15
order: 940
links:
  - type: verifies
    target: SYS-14YX19
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Authenticate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
