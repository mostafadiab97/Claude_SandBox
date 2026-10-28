---
id: TC-YXCMKZ
type: test-case
title: "Verify: Secure boot logs the connection state"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - accessibility
parent: INFO-Z4TW4B
order: 1130
links:
  - type: verifies
    target: SYS-W77D8P
    confirmed: 939eef8c8900
  - type: verifies
    target: SW-K76H4S
    confirmed: eb58fcaf9f95
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
