---
id: TC-WR8KT0
type: test-case
title: "Verify: Over-temperature monitor detects user preferences"
status: Obsolete
priority: Medium
owner: A. Hassan
tags:
  - i18n
  - release-2.0
parent: INFO-Z4TW4B
order: 1040
links:
  - type: verifies
    target: SYS-HKPNTA
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Limit audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
