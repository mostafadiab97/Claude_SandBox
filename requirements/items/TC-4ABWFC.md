---
id: TC-4ABWFC
type: test-case
title: "Verify: Secure boot displays safety limits"
status: Draft
priority: Medium
tags:
  - regulatory
  - release-1.0
  - performance
parent: INFO-Z4TW4B
order: 1150
links:
  - type: verifies
    target: SYS-RY2A1Y
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
