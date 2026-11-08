---
id: REQ-7PGG8BD
type: test-case
title: "Verify: Status LED limits the room temperature"
status: Draft
priority: High
owner: É. Laurent
tags:
  - i18n
  - release-1.0
former-id: TC-7AZQ40
parent: REQ-Y9VHHKA
order: b0M
links:
  - type: verifies
    target: REQ-3S6527M
    confirmed: e2bb9e80b6f4
  - type: verifies
    target: REQ-ECDD6JM
    confirmed: d9b394032de0
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
