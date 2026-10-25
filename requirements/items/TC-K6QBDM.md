---
id: TC-K6QBDM
type: test-case
title: "Verify: Enclosure logs audit records"
status: Draft
priority: High
owner: R. Nabil
tags:
  - security
  - release-1.0
  - customer-request
parent: INFO-MACGC3
order: 600
links:
  - type: verifies
    target: SYS-GW4A7W
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Validate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
