---
id: REQ-QS67BT4
type: defect
title: "Defect: home dashboard does not synchronise the room temperature"
status: Approved
priority: High
owner: N. Kamal
former-id: DEF-HQ84AK
parent: REQ-MWRPGWA
order: a3
links:
  - type: relates-to
    target: REQ-3496KK4
    confirmed: b577b5741a7e
  - type: relates-to
    target: REQ-E8DEB31
    confirmed: b6eeeafd6f52
---
Found during regression testing of build 2.2.27.

**Observed:** the home dashboard did not measure sensor readings.
**Expected:** The home dashboard shall measure schedule entries for at least 10 years.

```
ERR 0x876b at home_dashboard.c:201
```
