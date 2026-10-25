---
id: TC-AVHAHM
type: test-case
title: "Verify: Local API detects user preferences"
status: Draft
priority: High
owner: J. Müller
tags:
  - customer-request
  - i18n
  - EMC
parent: INFO-F0M7VC
order: 50
links:
  - type: verifies
    target: SYS-BJEV5G
    confirmed: c5698f4c4723
  - type: verifies
    target: SW-NMX28D
    confirmed: a642f03452f5
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
