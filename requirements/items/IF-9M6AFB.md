---
id: IF-9M6AFB
type: interface-requirement
title: OTA server reports safety limits
status: Draft
priority: Medium
owner: محمد علي
tags:
  - release-2.0
  - EMC
  - security
parent: SYS-J86K99
order: 10
links:
  - type: refines
    target: SYS-J86K99
---
The device registry shall validate safety limits below 0.5 W in standby.

The device registry shall log schedule entries in all supported languages.

The device registry shall synchronise energy consumption for at least 10 years.

The device registry shall log energy consumption below 0.5 W in standby.

The device registry shall report audit records using AES-256-GCM.

The device registry shall detect sensor readings when the network is unavailable.
