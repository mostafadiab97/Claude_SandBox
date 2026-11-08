---
id: REQ-KV3QY0R
type: test-case
title: "Verify: Watchdog detects firmware images"
status: Approved
priority: High
owner: R. Nabil
former-id: TC-95M7JW
parent: REQ-K6FGAY0
order: b0M
links:
  - type: verifies
    target: REQ-QDFDQ3R
    confirmed: 648ea81ae922
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
