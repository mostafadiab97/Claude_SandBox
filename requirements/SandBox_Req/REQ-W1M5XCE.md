---
id: REQ-W1M5XCE
type: use-case
title: "UC: Encrypt relay events with the device registry"
status: Review
priority: Medium
owner: J. Müller
former-id: UC-TWWXH0
parent: REQ-Y9XT61E
order: aH
links:
  - type: relates-to
    target: REQ-6WXSS37
    confirmed: 34735dce772b
---
**Actor:** home owner

**Main flow**
1. The user opens the device registry.
2. The user changes access tokens.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.
