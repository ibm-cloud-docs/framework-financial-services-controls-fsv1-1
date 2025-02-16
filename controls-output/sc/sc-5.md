---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SC-5 - Denial of Service Protection [FSv1.1]
{: #sc-5}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

SC-5 - 0
    : The information system protects against or limits the effects of the following types of denial of service attacks: [IBM Assignment: application and volumetric based attacks (OSI layers 3, 4, 6, and 7)] by employing [IBM Assignment: annual testing of the documented DoS and DDoS mitigation technologies].

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Accessing the public internet](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-internet)
- [Connectivity to {{site.data.keyword.cloud_notm}} services with private endpoints](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-ibm-services)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)

## NIST supplemental guidance
{: #nist-supplemental-guidance}

A variety of technologies exist to limit, or in some cases, eliminate the effects of denial of service attacks. For example, boundary protection devices can filter certain types of packets to protect information system components on internal organizational networks from being directly affected by denial of service attacks. Employing increased capacity and bandwidth combined with service redundancy may also reduce the susceptibility to denial of service attacks.





