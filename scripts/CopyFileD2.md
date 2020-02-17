Use this script to copy a file from an entry to the destination path on the specified system. This uses the dissolvable agent's HTTPS communication channel rather than scp or other out-of-band methods.

Example usage: `!CopyFileD2 destpath=/home/sansforensics/collectedbinaries/inv8_suspiciousPE1.exe.evil entryid=21@8 system=Analyst1`

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | javascript |
| Tags | util, server |
| Demisto Version | 0.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| system | The system to which we want to copy the file. |
| destpath | The full filesystem path and filename under which to save the file. |
| entryid | The ID of the war room entry containing the file to copy. |
| force | The overwrite file. |

## Outputs
---
There are no outputs for this script.