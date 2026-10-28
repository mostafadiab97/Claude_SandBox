---
id: REQ-4R058YT
type: test-case
title: "Verify: Cloud backend validates relay events"
status: Draft
priority: Medium
owner: K. Tanaka
former-id: TC-9Y4JJE
parent: REQ-8351896
order: b1d
links:
  - type: verifies
    target: REQ-0G1800J
    confirmed: d8b351a5c8e8
  - type: verifies
    target: REQ-8Z0F6ZY
    confirmed: e5b68f543837
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
