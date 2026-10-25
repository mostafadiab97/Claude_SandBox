---
id: TC-AMAV2Q
type: test-case
title: "Verify: Enclosure detects relay events"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - i18n
  - accessibility
parent: INFO-MACGC3
order: 1480
links:
  - type: verifies
    target: SYS-ZM6EM1
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
