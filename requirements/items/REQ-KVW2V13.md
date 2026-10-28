---
id: TC-NW6ZV9
type: test-case
title: "Verify: Tamper detection reports safety limits"
status: Draft
priority: High
owner: Y. Saber
tags:
  - customer-request
parent: INFO-Z4TW4B
order: 60
links:
  - type: verifies
    target: SYS-5RDA7K
    confirmed: 0b455862f511
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
