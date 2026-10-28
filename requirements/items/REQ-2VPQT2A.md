---
id: REQ-2VPQT2A
type: test-case
title: "Verify: Touch display logs the room temperature"
status: Review
owner: N. Kamal
former-id: TC-Z8M5MV
parent: REQ-Y9VHHKA
order: b0B
links:
  - type: verifies
    target: REQ-92WJY75
    confirmed: be2e7216bf63
  - type: verifies
    target: REQ-W6FF3VJ
    confirmed: 470d2dbe7eaf
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Log user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
