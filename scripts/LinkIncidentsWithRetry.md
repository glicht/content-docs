---
id: link-incidents-with-retry
title: Link Incidents With Retry
---

Avoids DB version errors when simultaneously running multiple linked incidents.

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | python |
| Tags |  |
| Demisto Version | 0.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| linkedIncidentIDs | The CSV list of related incident IDs. |
| retryLimit | The number of retries to perform after a failure. |

## Outputs
---
There are no outputs for this script.
