---
id: REQ-HRZWR46
type: test-case
title: "Verify: Main PCB switchs energy consumption"
status: Approved
owner: R. Nabil
former-id: TC-C6GNXF
parent: REQ-F9Z1FYS
order: b1O
links:
  - type: verifies
    target: REQ-7GP9R9J
    confirmed: da484be59d82
  - type: verifies
    target: REQ-ZEKWVQK
    confirmed: a470245f4ac9
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
