---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CP-6 - Alternate Storage Site [FSv1.1]
{: #cp-6}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

CP-6 (a)
    : Establishes an alternate storage site including necessary agreements to permit the storage and retrieval of information system backup information; and

CP-6 (b)
    : Ensures that the alternate storage site provides information security safeguards equivalent to that of the primary site.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)
- [Operational logging](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-operational)
- [Operational monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-operational)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| CP-6 (a) | - Check whether Cloud Object Storage bucket resiliency is set to cross region \n - Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region \n - Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated | 
| CP-6 (b) | - Check whether Cloud Object Storage bucket resiliency is set to cross region \n - Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region \n - Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated | 
{: caption="Rules for CP-6 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Alternate storage sites are sites that are geographically distinct from primary storage sites. An alternate storage site maintains duplicate copies of information and data in the event that the primary storage site is not available. Items covered by alternate storage site agreements include, for example, environmental conditions at alternate sites, access rules, physical and environmental protection requirements, and coordination of delivery/retrieval of backup media. Alternate storage sites reflect the requirements in contingency plans so that organizations can maintain essential missions/business functions despite disruption, compromise, or failure in organizational information systems.





