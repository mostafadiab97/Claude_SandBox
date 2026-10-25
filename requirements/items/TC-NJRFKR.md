---
id: TC-NJRFKR
type: test-case
title: "Verify: Backlight synchronises firmware images"
status: Draft
priority: Medium
owner: N. Kamal
parent: INFO-HTSZ15
order: 650
links:
  - type: verifies
    target: SYS-JWK81Y
  - type: verifies
    target: SW-GDVVE5
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
