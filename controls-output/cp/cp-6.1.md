---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CP-6 (1) - Separation from Primary Site [FSv1.1]
{: #cp-6.1}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

CP-6 (1) - 0
    : The organization identifies an alternate storage site that is separated from the primary storage site to reduce susceptibility to the same threats.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region 
- Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Threats that affect alternate storage sites are typically defined in organizational assessments of risk and include, for example, natural disasters, structural failures, hostile cyber attacks, and errors of omission/commission. Organizations determine what is considered a sufficient degree of separation between primary and alternate storage sites based on the types of threats that are of concern. For one particular type of threat (i.e., hostile cyber attack), the degree of separation between sites is less relevant.





