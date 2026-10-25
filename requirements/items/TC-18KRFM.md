---
id: TC-18KRFM
type: test-case
title: "Verify: Home dashboard reports error conditions"
status: Obsolete
priority: High
owner: Y. Saber
parent: INFO-J0FETE
order: 1040
links:
  - type: verifies
    target: SYS-3KEBNW
  - type: verifies
    target: SW-NA4WSY
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
