---
id: TC-HN3KGB
type: test-case
title: "Verify: Status LED detects audit records"
status: Approved
owner: R. Nabil
parent: INFO-HTSZ15
order: 1310
links:
  - type: verifies
    target: SYS-08Q79Y
    confirmed: 8a374fcf4b3a
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
