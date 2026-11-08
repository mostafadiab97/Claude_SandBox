---
id: REQ-B96W9VN
type: test-case
title: "Verify: Enclosure detects relay events"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - i18n
  - accessibility
former-id: TC-AMAV2Q
parent: REQ-F9Z1FYS
order: b1N
links:
  - type: verifies
    target: REQ-HTQ6KCV
    confirmed: bc2cbad41247
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
