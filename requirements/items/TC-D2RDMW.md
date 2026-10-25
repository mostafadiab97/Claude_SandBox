---
id: TC-D2RDMW
type: test-case
title: "Verify: Device registry limits humidity values"
status: Draft
priority: Medium
tags:
  - i18n
parent: INFO-7P4D8D
order: 910
links:
  - type: verifies
    target: SYS-59QMSN
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Validate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
