---
id: SW-0EZNQP
type: software-requirement
title: Detect audit records — detail
status: Review
priority: Medium
tags:
  - safety
  - performance
  - release-1.0
parent: SW-D8F6N6
order: 10
links:
  - type: refines
    target: SW-D8F6N6
    confirmed: 9cdbb3a331ff
---
The local API shall encrypt the operating mode in all supported languages.

The local API shall restore firmware images with an accuracy of ±0.5 °C.

The local API shall detect firmware images using AES-256-GCM.

The local API shall calibrate safety limits when the network is unavailable.

The local API shall validate error conditions when the network is unavailable.

The local API shall switch the operating mode after a power loss.
