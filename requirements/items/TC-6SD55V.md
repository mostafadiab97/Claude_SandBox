---
id: TC-6SD55V
type: test-case
title: "Verify: Main PCB notifys audit records"
status: Approved
priority: High
owner: N. Kamal
parent: INFO-MACGC3
order: 1250
links:
  - type: verifies
    target: SYS-3PN7YS
  - type: verifies
    target: SW-4ZJDE1
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Validate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
