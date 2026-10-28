---
id: TC-ZX2A1Z
type: test-case
title: "Regression: Regulation loop reports schedule entries"
status: Approved
priority: Medium
tags:
  - performance
  - EMC
parent: INFO-ECHASH
order: 1600
links:
  - type: verifies
    target: SYS-T6WXDY
    confirmed: e7cb857d34f0
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
