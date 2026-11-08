---
id: REQ-JRE296K
type: test-case
title: "Verify: Zigbee radio measures safety limits"
status: Draft
priority: Low
owner: A. Hassan
former-id: TC-0CDZYV
parent: REQ-67RQXCK
order: b1M
links:
  - type: verifies
    target: REQ-9CN4QTA
    confirmed: 758de3e92df3
  - type: verifies
    target: REQ-57X7EQ2
    confirmed: 8de9f47c9125
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
