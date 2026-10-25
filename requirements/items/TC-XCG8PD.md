---
id: TC-XCG8PD
type: test-case
title: "Verify: Enclosure stores firmware images"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - i18n
  - cost
parent: INFO-MACGC3
order: 960
links:
  - type: verifies
    target: SYS-WRCCVQ
  - type: verifies
    target: SW-0CA54W
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
