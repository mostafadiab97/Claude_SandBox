---
id: TC-ZRRYW5
type: test-case
title: "Verify: Cloud backend encrypts user preferences"
status: Approved
priority: High
owner: A. Hassan
parent: INFO-7P4D8D
order: 480
links:
  - type: verifies
    target: SYS-RGPMZF
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Measure the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
