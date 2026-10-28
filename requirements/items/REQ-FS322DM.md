---
id: TC-6Z2A02
type: test-case
title: "Verify: Status LED displays error conditions"
status: Draft
priority: High
owner: É. Laurent
tags:
  - customer-request
  - safety
  - i18n
parent: INFO-HTSZ15
order: 1530
links:
  - type: verifies
    target: SYS-933SE3
    confirmed: 87639e58a5eb
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
