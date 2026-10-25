---
id: TC-7AZQ40
type: test-case
title: "Verify: Status LED limits the room temperature"
status: Draft
priority: High
owner: É. Laurent
tags:
  - i18n
  - release-1.0
parent: INFO-HTSZ15
order: 850
links:
  - type: verifies
    target: SYS-TFXCHW
    confirmed: e2bb9e80b6f4
  - type: verifies
    target: SW-SKXKT9
    confirmed: d9b394032de0
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
