---
id: TC-SRPY18
type: test-case
title: "Verify: Secure boot notifys user preferences"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - regulatory
  - release-1.0
parent: INFO-Z4TW4B
order: 1050
links:
  - type: verifies
    target: SYS-A19YDT
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Switch the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
