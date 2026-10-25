---
id: TC-1KBV6P
type: test-case
title: "Verify: Enclosure calibrates access tokens"
status: Obsolete
owner: M. Farouk
tags:
  - connectivity
  - release-1.0
parent: INFO-MACGC3
order: 1550
links:
  - type: verifies
    target: SYS-7WAVP4
    confirmed: 0f9434a95be4
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Synchronise audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
