---
id: REQ-QFJP8JA
type: test-case
title: "Verify: Zigbee radio displays error conditions"
status: Approved
priority: High
owner: Y. Saber
tags:
  - i18n
  - connectivity
  - EMC
former-id: TC-AHW9BX
parent: REQ-67RQXCK
order: a3
links:
  - type: verifies
    target: REQ-8D3F6MP
    confirmed: a16febe00c06
  - type: verifies
    target: REQ-TWE4D4J
    confirmed: ccc7bd38a02a
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
