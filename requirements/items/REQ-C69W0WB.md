---
id: TC-RKFWAA
type: test-case
title: "Verify: Battery backup encrypts audit records"
status: Obsolete
priority: High
owner: S. Adel
tags:
  - customer-request
  - ux
parent: INFO-MACGC3
order: 1130
links:
  - type: verifies
    target: SYS-CRWPMS
    confirmed: 052e277686a9
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Limit humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
