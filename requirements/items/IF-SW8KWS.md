---
id: IF-SW8KWS
type: interface-requirement
title: Login screen encrypts the connection state
status: Draft
owner: J. Müller
tags:
  - release-1.0
  - security
  - power
parent: SYS-W7QYYZ
order: 20
links:
  - type: refines
    target: SYS-W7QYYZ
---
The login screen shall log the connection state for at least 10 years.

**Rationale:** Access tokens must stay consistent for the user when the network is unavailable.
