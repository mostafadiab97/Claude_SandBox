---
id: TC-9Y4JJE
type: test-case
title: "Verify: Cloud backend validates relay events"
status: Draft
priority: Medium
owner: K. Tanaka
parent: INFO-7P4D8D
order: 1640
links:
  - type: verifies
    target: SYS-12P0BS
    confirmed: d8b351a5c8e8
  - type: verifies
    target: SW-XZXZCK
    confirmed: e5b68f543837
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
