---
id: REQ-6PKH6ZA
type: test-case
title: "Verify: User account service switchs the connection state"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - customer-request
  - performance
  - EMC
former-id: TC-5S3D8A
parent: REQ-8351896
order: b04
links:
  - type: verifies
    target: REQ-5E4JPG7
    confirmed: 5220caa76f4b
  - type: verifies
    target: REQ-T440D0C
    confirmed: 3601ce92e4e2
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
