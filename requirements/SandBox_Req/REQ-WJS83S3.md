---
id: REQ-WJS83S3
type: test-case
title: "Verify: OTA server encrypts sensor readings"
status: Draft
priority: Medium
former-id: TC-5GCD7B
parent: REQ-8351896
order: b1b
links:
  - type: verifies
    target: REQ-Y9FVQ7Q
    confirmed: ebe6b95c0f3d
  - type: verifies
    target: REQ-EVH1N33
    confirmed: 68ee84cc7ff2
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Switch schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
