---
id: REQ-Z8TP365
type: test-case
title: "Verify: Home dashboard measures user preferences"
status: Review
priority: High
owner: محمد علي
former-id: TC-WA0GZN
parent: REQ-WR5ZJN9
order: b0l
links:
  - type: verifies
    target: REQ-5YMNSFC
    confirmed: 01ab1874e635
  - type: verifies
    target: REQ-JFY1Z87
    confirmed: 9cdba3274e95
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
