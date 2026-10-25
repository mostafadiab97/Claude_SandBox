---
id: TC-5MZNA0
type: test-case
title: "Verify: Device registry switchs the connection state"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - i18n
  - safety
  - security
parent: INFO-7P4D8D
order: 1600
links:
  - type: verifies
    target: SYS-E60WCX
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
