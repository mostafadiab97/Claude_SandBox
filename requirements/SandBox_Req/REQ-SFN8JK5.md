---
id: REQ-SFN8JK5
type: test-case
title: "Verify: Home dashboard detects the connection state"
status: Review
priority: High
owner: É. Laurent
tags:
  - connectivity
  - accessibility
  - EMC
former-id: TC-3K401R
parent: REQ-WR5ZJN9
order: aK
links:
  - type: verifies
    target: REQ-C5MK5TB
    confirmed: ba0d0f689c55
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
