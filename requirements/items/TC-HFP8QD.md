---
id: TC-HFP8QD
type: test-case
title: "Verify: Device registry stores audit records"
status: Obsolete
owner: N. Kamal
tags:
  - cost
  - release-1.0
parent: INFO-7P4D8D
order: 740
links:
  - type: verifies
    target: SYS-6MTAQR
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
