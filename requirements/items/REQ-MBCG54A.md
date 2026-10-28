---
id: TC-WW065V
type: test-case
title: "Verify: Device registry synchronises energy consumption"
status: Draft
owner: A. Hassan
parent: INFO-7P4D8D
order: 1650
links:
  - type: verifies
    target: SYS-7V2N1W
    confirmed: 595fd0fcde8d
  - type: verifies
    target: SW-2JRDMJ
    confirmed: 37b64617ffc6
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
