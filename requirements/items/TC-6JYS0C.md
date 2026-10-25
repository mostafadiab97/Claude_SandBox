---
id: TC-6JYS0C
type: test-case
title: "Verify: Regulation loop reports schedule entries"
status: Review
priority: Medium
owner: A. Hassan
parent: INFO-MS9DAG
order: 1150
links:
  - type: verifies
    target: SYS-T6WXDY
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Log firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
