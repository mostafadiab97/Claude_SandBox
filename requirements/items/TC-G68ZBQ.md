---
id: TC-G68ZBQ
type: test-case
title: "Verify: Device registry validates firmware images"
status: Approved
owner: N. Kamal
tags:
  - safety
  - release-1.0
parent: INFO-7P4D8D
order: 1570
links:
  - type: verifies
    target: SYS-JAKPTT
    confirmed: 83294ed50340
  - type: verifies
    target: SW-EB45BR
    confirmed: 74bdaa9f6306
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Report the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
