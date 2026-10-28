---
id: REQ-4ST49CS
type: test-case
title: "Verify: Status LED detects access tokens"
status: Obsolete
priority: High
owner: É. Laurent
tags:
  - regulatory
former-id: TC-ECD3HS
parent: REQ-Y9VHHKA
order: as
links:
  - type: verifies
    target: REQ-719VVV2
    confirmed: 86355bb1c3be
  - type: verifies
    target: REQ-DFQF1M3
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
