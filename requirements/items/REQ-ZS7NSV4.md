---
id: TC-MN2E0S
type: test-case
title: "Verify: Cloud backend validates audit records"
status: Draft
priority: Medium
owner: J. Müller
parent: INFO-7P4D8D
order: 840
links:
  - type: verifies
    target: SYS-KACHNP
    confirmed: 6d9bc192ec13
  - type: verifies
    target: SW-TNE9RX
    confirmed: d2e84a822cf8
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
