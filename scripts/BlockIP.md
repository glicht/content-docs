---
id: block-ip
title: Block IP
---

Blocks an IP address in a configured firewall.

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | javascript |
| Tags | firewall, checkpoint, panorama |
| Demisto Version | 0.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| ip | The IP address to block. |
| rulename | The rule name. |
| direction | The direction to block. Can be, "to", "from", or "both". The default is both. |
| ipname | The base name for the added IP Address/hosts inside the checkpoint db. |

## Outputs
---
There are no outputs for this script.
