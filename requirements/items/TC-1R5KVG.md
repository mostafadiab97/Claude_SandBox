---
id: TC-1R5KVG
type: test-case
title: "Verify: Boiler interface calibrates audit records"
status: Draft
priority: Low
owner: É. Laurent
tags:
  - i18n
  - accessibility
parent: INFO-MS9DAG
order: 1290
links:
  - type: verifies
    target: SYS-X7MMJ8
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
