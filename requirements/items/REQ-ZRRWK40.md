---
id: REQ-ZRRWK40
type: test-case
title: "Verify: Encryption layer calibrates firmware images"
status: Approved
priority: Medium
owner: S. Adel
former-id: TC-7MQA9R
parent: REQ-K6FGAY0
order: b1I
links:
  - type: verifies
    target: REQ-6JV91R3
    confirmed: fd1ef0a3e1ca
  - type: verifies
    target: REQ-55KGAGW
    confirmed: c978465ae5a5
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
