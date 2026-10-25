---
id: TC-NQ8XMV
type: test-case
title: "Verify: Pairing process limits access tokens"
status: Draft
priority: High
owner: محمد علي
tags:
  - customer-request
  - cost
parent: INFO-F0M7VC
order: 680
links:
  - type: verifies
    target: SYS-X1DW4B
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
