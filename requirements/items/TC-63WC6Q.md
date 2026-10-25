---
id: TC-63WC6Q
type: test-case
title: "Verify: Secure boot displays firmware images"
status: Review
owner: محمد علي
tags:
  - security
  - cost
  - i18n
parent: INFO-Z4TW4B
order: 740
links:
  - type: verifies
    target: SYS-RZQXR0
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Authenticate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
