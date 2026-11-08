---
id: REQ-HW3TG06
type: test-case
title: "Verify: Mobile app encrypts safety limits"
status: Review
priority: Medium
owner: S. Adel
former-id: TC-BGTA9C
parent: REQ-WR5ZJN9
order: b1L
links:
  - type: verifies
    target: REQ-2PXRV1Y
    confirmed: c844415dcddc
  - type: verifies
    target: REQ-32F8R7P
    confirmed: e55ee221dfd4
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
