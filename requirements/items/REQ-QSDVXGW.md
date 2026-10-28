---
id: REQ-QSDVXGW
type: use-case
title: "UC: Validate schedule entries with the pairing process"
status: Draft
priority: Low
owner: R. Nabil
tags:
  - release-1.0
  - release-2.0
  - security
former-id: UC-400ZW0
parent: REQ-X5TXBRB
order: aC
links:
  - type: relates-to
    target: REQ-8TVXMWR
    confirmed: 994ecb1eff6f
---
**Actor:** home owner

**Main flow**
1. The user opens the pairing process.
2. The user changes access tokens.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.
