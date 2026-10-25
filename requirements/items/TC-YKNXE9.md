---
id: TC-YKNXE9
type: test-case
title: "Verify: Pairing process stores audit records"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - accessibility
  - i18n
parent: INFO-F0M7VC
order: 200
links:
  - type: verifies
    target: SYS-DHBZX2
    confirmed: f269617e5175
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Switch audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
