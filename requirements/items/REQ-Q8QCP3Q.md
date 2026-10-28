---
id: TC-XFNW97
type: test-case
title: "Verify: Over-temperature monitor logs the connection state"
status: Draft
owner: M. Farouk
tags:
  - regulatory
  - accessibility
  - performance
parent: INFO-Z4TW4B
order: 70
links:
  - type: verifies
    target: SYS-KZYDJR
    confirmed: c4c96610c247
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Report schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
