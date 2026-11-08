---
id: REQ-VNP9XCF
type: test-case
title: "Verify: Status LED measures the operating mode"
status: Approved
owner: J. Müller
former-id: TC-R2QZMC
parent: REQ-Y9VHHKA
order: b0l
links:
  - type: verifies
    target: REQ-VQQJASQ
    confirmed: 1b092edc3073
  - type: verifies
    target: REQ-C58NWQ8
    confirmed: 54e0e57fc0f2
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Restore user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
