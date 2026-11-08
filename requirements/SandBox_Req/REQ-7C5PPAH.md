---
id: REQ-7C5PPAH
type: interface-requirement
title: OTA server reports safety limits
status: Draft
priority: Medium
owner: محمد علي
tags:
  - release-2.0
  - EMC
  - security
former-id: IF-9M6AFB
parent: REQ-Q9W4EZ1
order: a0
links:
  - type: refines
    target: REQ-Q9W4EZ1
    confirmed: cd639bbeedd1
---
The device registry shall validate safety limits below 0.5 W in standby.

The device registry shall log schedule entries in all supported languages.

The device registry shall synchronise energy consumption for at least 10 years.

The device registry shall log energy consumption below 0.5 W in standby.

The device registry shall report audit records using AES-256-GCM.

The device registry shall detect sensor readings when the network is unavailable.
