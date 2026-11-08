---
id: REQ-0HN1WE3
type: defect
title: "Defect: Zigbee radio does not encrypt relay events"
status: Draft
owner: J. Müller
former-id: DEF-747W47
parent: REQ-YW554H8
order: a7
links:
  - type: relates-to
    target: REQ-5GSR3P0
    confirmed: ae4430bf0a2c
  - type: relates-to
    target: REQ-EQZCZSV
    confirmed: b5edec3ba8f3
---
Found during regression testing of build 2.4.17.

**Observed:** the Zigbee radio did not synchronise access tokens.
**Expected:** The Zigbee radio shall synchronise relay events without user interaction.

```
ERR 0xc0ed at Zigbee_radio.c:313
```
