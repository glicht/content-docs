---
id: port-listen-check
title: Port Listen Check
---

Checks whether a port was open on a given host.

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | python |
| Tags | - |
| Demisto Version | 0.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| host | The hostname to check. |
| port | The port to check. |

## Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| portOpen | Whether the given port on a host was open. Returns true if it is. | boolean |
