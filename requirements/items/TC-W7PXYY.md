---
id: TC-W7PXYY
type: test-case
title: "Verify: Status LED displays humidity values"
status: Obsolete
priority: High
owner: J. Müller
tags:
  - security
parent: INFO-HTSZ15
order: 1510
links:
  - type: verifies
    target: SYS-7AH6RP
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Switch firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
