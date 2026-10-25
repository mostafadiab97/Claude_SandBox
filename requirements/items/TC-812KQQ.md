---
id: TC-812KQQ
type: test-case
title: "Verify: Status LED restores the room temperature"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - release-2.0
  - customer-request
parent: INFO-HTSZ15
order: 420
links:
  - type: verifies
    target: SYS-PY3FTT
    confirmed: 028b4e4661e2
  - type: verifies
    target: SW-JH3JZR
    confirmed: dbe3045309c3
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Encrypt relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
