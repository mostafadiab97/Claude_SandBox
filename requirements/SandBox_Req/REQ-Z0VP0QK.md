---
id: REQ-Z0VP0QK
type: design-element
title: Design element with a code block
status: Approved
tags:
  - i18n
  - accessibility
  - release-2.0
former-id: DE-3FF89G
parent: REQ-6H15AV2
order: a7
---
```c
int regulate(float setpoint, float measured) {
  return setpoint - measured > 0.5f ? HEAT_ON : HEAT_OFF;
}
```
