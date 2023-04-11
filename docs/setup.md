| [Home](../README.md) |
|--------------------------------------------|

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.
2. From the list of solution pack that appears, search for and select `Armis`.
3. Click the `Armis` solution pack card.
4. Click **Install** on the bottom to begin installation.

## Prerequisites

The `Armis` solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| **Solution Pack Name**        | **Version**     | **Purpose**                                                         |
|:------------------------------|:----------------|:--------------------------------------------------------------------|
| SOAR Frame                    | v2.1.0 or later | Required for Alerts, Assets, Incident Response modules.             |
| SOC Simulator                 | v1.0.2 or later | Required for Scenario Module and SOC Simulator connector.           |
| OT - Asset Management         | v1.0.0 or later | Required for Asset Modules and playbooks.                           |
| OT - Vulnerability Management | v1.0.0 or later | Required for CVEs, ICS Advisory and KEV Alert Module and playbooks. |

# Configuration

For optimal performance of `Armis` solution pack, you can install and configure the connectors that help with the following:

>* **Armis** connector to fetch Alert, Assets and CVEs from Armis. To configure and use the Armis connector, refer to [Configuring Armis](https://docs.fortinet.com/document/fortisoar/1.0.0/armis/485/armis-v1-0-0)
>* **Fortinet FortiDeceptor** connector to Deploy Decoy on asset. To configure and use the Fortinet FortiDeceptor connector, refer to [Configuring Fortinet FortiDeceptor](https://docs.fortinet.com/document/fortisoar/1.0.0/fortinet-fortideceptor/520/fortinet-fortideceptor-v1-0-0)
>* **Fortinet FortiEDR** connector to Isolate collectors. To configure and use the Fortinet FortiEDR connector, refer to [Configuring Fortinet FortiEDR](https://docs.fortinet.com/document/fortisoar/1.3.0/fortinet-fortiedr/161/fortinet-fortiedr-v1-3-0)
>* **ServiceNow** connector to raise tickets. To configure and use the ServiceNow connector, refer to [Configuring ServiceNow](https://docs.fortinet.com/document/fortisoar/3.2.0/servicenow/384/servicenow-v3-2-0)