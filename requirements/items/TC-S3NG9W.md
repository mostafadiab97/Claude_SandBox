---
id: TC-S3NG9W
type: test-case
title: "Verify: Tamper detection calibrates safety limits"
status: Review
owner: É. Laurent
tags:
  - i18n
parent: INFO-Z4TW4B
order: 1000
links:
  - type: verifies
    target: SYS-XM6K6N
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
