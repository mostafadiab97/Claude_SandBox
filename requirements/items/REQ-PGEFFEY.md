---
id: TC-HQF9JF
type: test-case
title: "Verify: Enclosure stores schedule entries"
status: Approved
owner: S. Adel
parent: INFO-MACGC3
order: 720
links:
  - type: verifies
    target: SYS-PCB26E
    confirmed: 1f9a2a50a4bc
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Synchronise access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
