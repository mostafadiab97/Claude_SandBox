---
id: TC-7XSWFW
type: test-case
title: "Verify: OTA server restores schedule entries"
status: Draft
priority: Medium
owner: S. Adel
tags:
  - i18n
  - release-1.0
parent: INFO-7P4D8D
order: 630
links:
  - type: verifies
    target: SYS-0K19ZT
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
