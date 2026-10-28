---
id: TC-ECD3HS
type: test-case
title: "Verify: Status LED detects access tokens"
status: Obsolete
priority: High
owner: É. Laurent
tags:
  - regulatory
parent: INFO-HTSZ15
order: 550
links:
  - type: verifies
    target: SYS-FNTHY0
    confirmed: 86355bb1c3be
  - type: verifies
    target: SW-YG9MA7
    confirmed: 44025c9425c4
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
