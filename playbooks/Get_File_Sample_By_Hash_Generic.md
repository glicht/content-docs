---
id: get-file-sample-by-hash-generic
title: Get File Sample by Hash Generic
---

Returns to the War Room, a file sample, correlating from a file hash using one or more products.

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks
* Get File Sample By Hash - Carbon Black Enterprise Response
* Get File Sample By Hash - Cylance Protect

### Integrations
This playbook does not use any integrations.

### Scripts
This playbook does not use any scripts.

### Commands
This playbook does not use any commands.

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Source** | **Required** |
| --- | --- | --- | --- | --- |
| MD5 | Returns the file sample from the input MD5 hash. | MD5 | File | Optional |
| SHA256 | Returns the file sample from the input SHA256 hash. | SHA256 | File | Optional |

## Playbook Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| File | The file sample object. | unknown |

![Get_File_Sample_By_Hash_Generic](https://github.com/ElazarK/content-docs/blob/master/images/playbooks/Get_File_Sample_By_Hash_Generic.png) 
