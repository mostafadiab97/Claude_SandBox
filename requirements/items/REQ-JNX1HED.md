---
id: REQ-JNX1HED
type: test-case
title: "Verify: Enclosure logs the connection state"
status: Draft
owner: A. Hassan
former-id: TC-BTTBVQ
parent: REQ-F9Z1FYS
order: b1V
links:
  - type: verifies
    target: REQ-VKW8KMD
    confirmed: c526dc6b205d
  - type: verifies
    target: REQ-TH6C89S
    confirmed: ddd704c50367
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
