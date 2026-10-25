---
id: TC-V9J7D8
type: test-case
title: "Verify: Main PCB encrypts the connection state"
status: Draft
priority: High
owner: J. Müller
parent: INFO-MACGC3
order: 1280
links:
  - type: verifies
    target: SYS-T8N5MR
    confirmed: 1d9e96e23af9
  - type: verifies
    target: SW-3S3JPB
    confirmed: 0d5286c028bc
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
