---
id: TC-2PJFPZ
type: test-case
title: "Verify: Enclosure reports relay events"
status: Obsolete
owner: M. Farouk
parent: INFO-MACGC3
order: 1310
links:
  - type: verifies
    target: SYS-3W1S3B
    confirmed: a83839a61248
  - type: verifies
    target: SW-MMKFXA
    confirmed: 4e72756bdfca
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
