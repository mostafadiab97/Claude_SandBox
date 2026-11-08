---
id: REQ-79VC1NR
type: test-case
title: "Verify: Enclosure stores firmware images"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - i18n
  - cost
former-id: TC-XCG8PD
parent: REQ-F9Z1FYS
order: b0X
links:
  - type: verifies
    target: REQ-7AV7MGG
    confirmed: 22615937890b
  - type: verifies
    target: REQ-8BZ2WF3
    confirmed: c33a35847fa5
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
