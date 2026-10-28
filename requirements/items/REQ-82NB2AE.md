---
id: REQ-82NB2AE
type: test-case
title: "Verify: Home dashboard restores energy consumption"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - security
  - regulatory
former-id: TC-1RD5AV
parent: REQ-WR5ZJN9
order: an
links:
  - type: verifies
    target: REQ-6ESJ1D4
    confirmed: b0a3b18f1cfd
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
