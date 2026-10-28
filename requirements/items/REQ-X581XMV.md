---
id: REQ-X581XMV
type: test-case
title: "Verify: Encryption layer reports safety limits"
status: Draft
owner: S. Adel
former-id: TC-A7DMTK
parent: REQ-K6FGAY0
order: aJ
links:
  - type: verifies
    target: REQ-NZV7M9Z
    confirmed: d4703e1835f9
  - type: verifies
    target: REQ-B3W3WPF
    confirmed: dd6fbda1233e
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Notify error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
