---
id: TC-8NT63R
type: test-case
title: "Verify: Enclosure notifys error conditions"
status: Draft
priority: Low
owner: S. Adel
tags:
  - regulatory
  - security
  - customer-request
parent: INFO-MACGC3
order: 650
links:
  - type: verifies
    target: SYS-QRF69W
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
