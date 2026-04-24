---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
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



## NIST supplemental guidance
{: #nist-supplemental-guidance}

System-level information includes, for example, system-state information, operating system and application software, and licenses. User-level information includes any information other than system-level information. Mechanisms employed by organizations to protect the integrity of information system backups include, for example, digital signatures and cryptographic hashes. Protection of system backup information while in transit is beyond the scope of this control. Information system backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information.
