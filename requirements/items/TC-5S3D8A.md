---
id: TC-5S3D8A
type: test-case
title: "Verify: User account service switchs the connection state"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - customer-request
  - performance
  - EMC
parent: INFO-7P4D8D
order: 670
links:
  - type: verifies
    target: SYS-2NPFB8
    confirmed: 5220caa76f4b
  - type: verifies
    target: SW-SV5WNT
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
