| [Home](../README.md) |
|--------------------------------------------|

# Contents

The `**Armis**` solution pack contains the following resources.

## Connectors

|**Name**|**Version**|**Description**|
| :- | :- | :- |
|  Armis  |  v1.1.0 or later  |  Armis connector protects from cyber threats created by the onslaught of unmanaged IoT devices. This connector facilitates operations to get alerts and devices list, update the status of alerts, tag, and untag devices.  |
|  Fortinet FortiDeceptor  |  v1.0.0 or later  |  FortiDeceptor is a deception-based Breach Protection Deceive, Expose and Eliminate External and Internal Threats.  |
|  Fortinet FortiEDR  |  v1.3.0 or later  |  FortiEDR protects endpoints pre and post-infection, stopping data breaches in real-time and automatically orchestrating incident investigation and response. This connector facilitates automated operations related to events, forensics, and collectors.  |
|  ServiceNow  |  v3.2.0 or later  |  ServiceNow connector provides functionality to create, read, update, and delete records of Table and Catalog type.  |

## Scenario Record Set

|**Name**|**Description**|
| :- | :- |
|  Armis Scenario  |  This Scenario adds 10 CVEs, 5 ICS Advisory, 5 KEV Alert and "[Threat] Ransomware Communication Detected" Alert. These data can be used to understand Armis Use Case.  |

## Playbook Collection

|02 - Use Case - Armis |
| :- |

**Playbook Name**|**Description**|
| :- | :- |
|  Scenario - Create Armis Alert  | Playbook generated sample CVEs, ICS Advisory, KEV Alert and Alert to understand Armis Use Case. |
|  > Create Scenario KEV Alert  |  Playbook creates scenario KEV Alert.  |
|  Get Alert Details  |  Playbook executes post alert creation(source Armis) and get Assets and CVEs from Armis.  |
|  > Create Asset Record  |  This PB will create Asset Record and fetch CVEs from Armis and correlate Asset with CVEs, ICS Advisory and KEV Alert  |
|  On Asset Creation  |  On Asset Creation (from Armis) link it to existing KEV Alert (if any of same vendor).  |
|  > Get Vulnerability Matches By Device ID  |  This Playbook will fetch vulnerability matches in Armis by device id provided.  |
|  Deploy Decoy And Isolate Assets  |  This Playbook will deploy FortiDECEPTOR decoy on assets, isolates assets in FortiEDR and raise ticket in Service Now.  |
|  Get All Assets  |  Retrieve all the devices from Armis  |

>**Warning:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.
