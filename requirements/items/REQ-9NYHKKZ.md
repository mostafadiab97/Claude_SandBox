---
id: REQ-9NYHKKZ
type: test-case
title: "Verify: Battery backup logs error conditions"
status: Approved
priority: High
owner: R. Nabil
tags:
  - release-1.0
  - release-2.0
  - i18n
former-id: TC-6WRZDR
parent: REQ-F9Z1FYS
order: b14
links:
  - type: verifies
    target: REQ-KVQ8Z5K
    confirmed: 144fa7466d8d
  - type: verifies
    target: REQ-QKEC0QE
    confirmed: 0dcb4ff55039
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Detect schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
