---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CP-9 - Information System Backup [FSv1.1]
{: #cp-9}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

CP-9 (a)
    : Conducts backups of user-level information contained in the information system _[IBM Assignment: daily incremental; weekly full]_;

CP-9 (b)
    : Conducts backups of system-level information contained in the information system _[IBM Assignment: daily incremental; weekly full]_;

CP-9 (c)
    : Conducts backups of information system documentation including security-related documentation _[IBM Assignment: daily incremental; weekly full]_; and

CP-9 (d)
    : Protects the confidentiality, integrity, and availability of backup information at storage locations.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| CP-9 (b) | - Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region \n - Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated | 
| CP-9 (d) | - Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region \n - Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated | 
{: caption="Rules for CP-9 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

System-level information includes, for example, system-state information, operating system and application software, and licenses. User-level information includes any information other than system-level information. Mechanisms employed by organizations to protect the integrity of information system backups include, for example, digital signatures and cryptographic hashes. Protection of system backup information while in transit is beyond the scope of this control. Information system backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information.





