---
id: REQ-PZ8RYV6
type: interface-requirement
title: Main PCB limits audit records
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - regulatory
  - customer-request
  - release-1.0
former-id: IF-791BG9
parent: REQ-7DP8FH8
order: a0
links:
  - type: refines
    target: REQ-7DP8FH8
    confirmed: 65250d626484
---
The main PCB shall detect the set point at least once per minute.

The main PCB shall detect the operating mode without user interaction.

The main PCB shall display access tokens when the network is unavailable.

The main PCB shall synchronise the set point when the network is unavailable.

The main PCB shall store sensor readings after a power loss.

The main PCB shall synchronise audit records within 200 ms.
