---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AU-8 (1) - Synchronization with Authoritative Time Source [FSv1.1]
{: #au-8.1}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The information system:

AU-8 (1) (a)
    : Compares the internal information system clocks _[IBM Assignment: authoritative time source: servertime.service.softlayer.com]_ with _[IBM Assignment: at least hourly]_; and

AU-8 (1) (b)
    : Synchronizes the internal system clocks to the authoritative time source when the time difference is greater than _[Assignment: organization-defined time period]_.

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control enhancement provides uniformity of time stamps for information systems with multiple system clocks and systems connected over a network.





