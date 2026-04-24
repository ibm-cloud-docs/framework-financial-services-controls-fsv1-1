---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
---

{{site.data.keyword.attribute-definition-list}}


# SC-7 - Boundary Protection [FSv1.1]
{: #sc-7}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The information system:

SC-7 (a)
    : Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system;

SC-7 (b)
    : Implements subnetworks for publicly accessible system components that are _[Selection: physically; logically]_ separated from internal organizational networks; and

SC-7 (c)
    : Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security architecture.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization "service delivery" and "corporate" environments must be maintained as separate environments. That is, clear physical and/or logical boundaries separating the two environments must exist.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Accessing the public internet](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-internet)
- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)
- [Connectivity to {{site.data.keyword.cloud_notm}} services with private endpoints](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-services)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)



## NIST supplemental guidance
{: #nist-supplemental-guidance}

Managed interfaces include, for example, gateways, routers, firewalls, guards, network-based malicious code analysis and virtualization systems, or encrypted tunnels implemented within a security architecture (e.g., routers protecting firewalls or application gateways residing on protected subnetworks). Subnetworks that are physically or logically separated from internal networks are referred to as demilitarized zones or DMZs. Restricting or prohibiting interfaces within organizational information systems includes, for example, restricting external web traffic to designated web servers within managed interfaces and prohibiting external traffic that appears to be spoofing internal addresses. Organizations consider the shared nature of commercial telecommunications services in the implementation of security controls associated with the use of such services. Commercial telecommunications services are commonly based on network components and consolidated management systems shared by all attached commercial customers, and may also include third party-provided access lines and other service elements. Such transmission services may represent sources of increased risk despite contract security provisions.
