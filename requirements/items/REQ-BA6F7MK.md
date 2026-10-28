---
id: TC-6ZPVZ2
type: test-case
title: "Verify: Menu system reports sensor readings"
status: Draft
owner: R. Nabil
parent: INFO-HTSZ15
order: 1280
links:
  - type: verifies
    target: SYS-S318HE
    confirmed: a8739639e10d
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Restore relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
