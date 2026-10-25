---
id: TC-FFN7QA
type: test-case
title: "Verify: Mobile app stores humidity values"
status: Approved
priority: High
owner: L. Samir
tags:
  - i18n
  - ux
  - release-2.0
parent: INFO-J0FETE
order: 870
links:
  - type: verifies
    target: SYS-14BTQV
    confirmed: 887219d0a50f
  - type: verifies
    target: SW-6ZNEMR
    confirmed: 8cdaa51b3615
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
