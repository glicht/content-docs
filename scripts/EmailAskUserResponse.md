---
id: email-ask-user-response
title: Email Ask User Response
---

Extract a user's response from `EmailAskUser reply`. Returns the first textual response line of the provided entry that contains the reply body. Use `${lastCompletedTaskEntries}` to analyze the previous playbook task containing the user's reply.

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | javascript |
| Tags | Condition |
| Demisto Version | 0.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| responseEntryId | The entry ID where `EmailAskUser` will complete when the user replies. |

## Outputs
---
There are no outputs for this script.
