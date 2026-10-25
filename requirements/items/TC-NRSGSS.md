---
id: TC-NRSGSS
type: test-case
title: "Verify: Touch display stores audit records"
status: Draft
priority: High
owner: A. Hassan
tags:
  - connectivity
  - customer-request
  - accessibility
parent: INFO-HTSZ15
order: 570
links:
  - type: verifies
    target: SYS-TB9F0A
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
