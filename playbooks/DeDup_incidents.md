---
id: dedupincidents
title: DeDup Incidents
---

Checks for duplicate incidents for the current incident, and close it if any duplicate has found. 

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

## Sub-playbooks
This playbook does not use any sub-playbooks.

## Integrations
This playbook does not use any integrations.

## Scripts
* CloseInvestigationAsDuplicate
* FindSimilarIncidents

## Commands
This playbook does not use any commands.

## Playbook Inputs  
---

| **Name** | **Description** | **Default Value** | **Required** |
| --- | --- | --- | --- | 
| similarIncidentKeys | The identical incident keys. | - | Optional |
| similarLabels | The identical similar labels keys. You allow difference in X words between labels. For example, the input: Email\\subject:2,Email\\from Will demand: 1. Email\\from to be identical 2. Email\\subject to be similar with 2 max words difference | - | Optional |
| similarContextKeys | Identical Similar context keys. You allow difference in X words between values.  | - | Optional |
| similarCustomFields | Identical Similar custom fields. You allow difference in X words between values. | - | Optional |
| hoursBack | Checks incidents within X hours back. | 24 | Optional |

## Playbook Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| isSimilarIncidentFound | Whether the similar incident was found. Must be, "true" or "false". | unknown |

![DeDup_incidents](https://github.com/ElazarK/content-docs/blob/master/images/playbooks/DeDup_incidents.png)
