---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
---

{{site.data.keyword.attribute-definition-list}}


# CP-7 - Alternate Processing Site [FSv1.1]
{: #cp-7}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

CP-7 (a)
    : Establishes an alternate processing site including necessary agreements to permit the transfer and resumption of _[IBM Assignment: customer applications must failover production workload to an alternate site for a period of five (5) consecutive days]_ for essential missions/business functions within _[IBM Assignment: customer defined RTO/RPO for application]_ when the primary processing capabilities are unavailable;

CP-7 (b)
    : Ensures that equipment and supplies required to transfer and resume operations are available at the alternate processing site or contracts are in place to support delivery to the site within the organization-defined time period for transfer/resumption; and

CP-7 (c)
    : Ensures that the alternate processing site provides information security safeguards equivalent to those of the primary site.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Where failover is used, applications must failover and maintain production workload to an alternate site for a period of five (5) consecutive days.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)
- [High availability overview](/docs/framework-financial-services?topic=framework-financial-services-shared-high-availability)
- [Operational logging](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-operational)
- [Operational monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-operational)



## NIST supplemental guidance
{: #nist-supplemental-guidance}

Alternate processing sites are sites that are geographically distinct from primary processing sites. An alternate processing site provides processing capability in the event that the primary processing site is not available. Items covered by alternate processing site agreements include, for example, environmental conditions at alternate sites, access rules, physical and environmental protection requirements, and coordination for the transfer/assignment of personnel. Requirements are specifically allocated to alternate processing sites that reflect the requirements in contingency plans to maintain essential missions/business functions despite disruption, compromise, or failure in organizational information systems.
