---
id: REQ-0W6WEK9
type: test-case
title: "Verify: Device registry calibrates error conditions"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - EMC
  - regulatory
  - cost
former-id: TC-DDJ6JZ
parent: REQ-8351896
order: as
links:
  - type: verifies
    target: REQ-9W3N8PR
    confirmed: df8c85150795
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Authenticate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
