---
id: REQ-8SD6VN3
type: test-case
title: "Verify: Enclosure calibrates firmware images"
status: Draft
priority: Low
owner: É. Laurent
former-id: TC-XVZ3TE
parent: REQ-F9Z1FYS
order: aD
links:
  - type: verifies
    target: REQ-79Q9433
    confirmed: c20a655c1dc7
  - type: verifies
    target: REQ-SH5BNSJ
    confirmed: eac962e658d0
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
