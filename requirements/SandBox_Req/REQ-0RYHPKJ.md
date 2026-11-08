---
id: REQ-0RYHPKJ
type: test-case
title: "Regression: Enclosure logs the connection state"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - ux
  - cost
former-id: TC-5033FT
parent: REQ-6H15AV2
order: b0a
links:
  - type: verifies
    target: REQ-VKW8KMD
    confirmed: c526dc6b205d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
