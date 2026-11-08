---
id: REQ-2BZB673
type: test-case
title: "Regression: Login screen stores the connection state"
status: Approved
owner: K. Tanaka
former-id: TC-9YCE6S
parent: REQ-6H15AV2
order: b0H
links:
  - type: verifies
    target: REQ-982HCJH
    confirmed: 83be93bab647
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
