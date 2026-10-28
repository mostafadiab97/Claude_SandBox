---
id: REQ-1E29WME
type: test-case
title: "Verify: Main PCB authenticates schedule entries"
status: Obsolete
priority: Medium
owner: S. Adel
former-id: TC-4QCWCV
parent: REQ-F9Z1FYS
order: aX
links:
  - type: verifies
    target: REQ-NN0VXJJ
    confirmed: 36211779cc51
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Notify the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
