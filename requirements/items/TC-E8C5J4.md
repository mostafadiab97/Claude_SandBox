---
id: TC-E8C5J4
type: test-case
title: "Verify: Encryption layer notifys humidity values"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - accessibility
  - EMC
parent: INFO-Z4TW4B
order: 1330
links:
  - type: verifies
    target: SYS-1F01HM
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Authenticate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
