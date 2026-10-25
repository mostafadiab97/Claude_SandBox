---
id: TC-FT21R4
type: test-case
title: "Verify: Secure boot notifys the operating mode"
status: Draft
priority: Medium
owner: S. Adel
parent: INFO-Z4TW4B
order: 780
links:
  - type: verifies
    target: SYS-4MWCBY
  - type: verifies
    target: SW-H6KK0F
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Display the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
