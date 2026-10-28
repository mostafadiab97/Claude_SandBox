---
id: TC-QGJBH3
type: test-case
title: "Verify: Device registry reports the room temperature"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - customer-request
  - connectivity
parent: INFO-7P4D8D
order: 980
links:
  - type: verifies
    target: SYS-PYK237
    confirmed: 8258f49e00ae
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
