---
id: REQ-WSD7EZZ
type: test-case
title: "Regression: User account service logs user preferences"
status: Obsolete
owner: M. Farouk
tags:
  - i18n
  - regulatory
  - performance
former-id: TC-49P7W9
parent: REQ-6H15AV2
order: b0t
links:
  - type: verifies
    target: REQ-BWMZ077
    confirmed: f3aedc76f0ed
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
