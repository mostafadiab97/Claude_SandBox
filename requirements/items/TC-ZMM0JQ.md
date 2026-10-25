---
id: TC-ZMM0JQ
type: test-case
title: "Verify: Regulation loop limits safety limits"
status: Draft
priority: High
owner: N. Kamal
parent: INFO-MS9DAG
order: 640
links:
  - type: verifies
    target: SYS-3C9GVX
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
