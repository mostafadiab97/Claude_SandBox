---
id: TC-NAS8NX
type: test-case
title: "Verify: Touch display logs the connection state"
status: Draft
owner: N. Kamal
parent: INFO-HTSZ15
order: 1260
links:
  - type: verifies
    target: SYS-PKAKPD
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
