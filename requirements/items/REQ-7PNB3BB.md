---
id: REQ-7PNB3BB
type: test-case
title: "Verify: Secure boot switchs relay events"
status: Approved
owner: N. Kamal
former-id: TC-6ASJRH
parent: REQ-K6FGAY0
order: a9
links:
  - type: verifies
    target: REQ-6PB57PX
    confirmed: 3dd7a8ccfac1
  - type: verifies
    target: REQ-3B0EQ0W
    confirmed: da530757de05
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
