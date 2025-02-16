---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AC-4 - Information Flow Enforcement [FSv1.1]
{: #ac-4}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

AC-4 - 0
    : The information system enforces approved authorizations for controlling the flow of information within the system and between interconnected systems based on [Assignment: organization-defined information flow control policies].

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization must document all information flows that involve the transfer of customer data.  An information flow control policy must be developed and maintained that indicates the source and destination of each flow, the system of record and whether the information is altered during transmission.
- The organization shall maintain a catalog of all customer metadata processed and/or transmitted by the organization on behalf of the customer.  Metadata should be defined by each customer.
- The organization "service delivery" and "corporate" environments must be maintained as separate environments. That is, clear physical and/or logical boundaries separating the two environments must exist.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port 
- Check whether Event Streams network access is restricted to a specific IP range 
- Check whether Virtual Servers for VPC instance doesn't have a floating IP 
- Check whether Application Load Balancer for VPC has public access disabled 
- Check whether OpenShift clusters are accessible only by using private endpoints 
- Check whether Cloud Object Storage quota enforcement is off for buckets that are configured to use Activity Tracker Event Routing 
- Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IP addresses 
- Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints 
- Check whether Event Streams is accessible only by using private endpoints 
- Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints 
- Check whether Virtual Private Cloud (VPC) has no public gateways attached 
- Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port 
- Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached 
- Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning 
- Check whether App ID redirect URIs are not using wildcards (*) 
- Check whether at least # Virtual Private Cloud (VPC)s have been created 
- Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled 
- Check whether at least # instances of Transit Gateway have been created 
- Check whether Cloud Object Storage network access is restricted to a specific IP range 
- Check whether account has at least one VPN or Direct Link configured 
- Check whether Virtual Private Cloud (VPC) classic access is disabled 
- Check whether Virtual Private Cloud (VPC) has no rules in the default security group 
- Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached 
- Check whether Container Registry image pushes and pulls take place only over private endpoints 
- Check whether Virtual Servers for VPC instance has the minimum # interfaces 
- Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached 
- Check whether Hyper Protect Crypto Services is accessible only through private endpoints 
- Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IP addresses 
- Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones 
- Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs) 
- Check whether a security group other than the default for Virtual Private Cloud is attached to all endpoints 
- Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to RDP port 
- Check whether App ID redirect URIs are not using localhost or 127.0.0.1 
- Check whether Cloud Object Storage is accessible only by using private endpoints 
- Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to SSH port 
- Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Information flow control regulates where information is allowed to travel within an information system and between information systems (as opposed to who is allowed to access the information) and without explicit regard to subsequent accesses to that information. Flow control restrictions include, for example, keeping export-controlled information from being transmitted in the clear to the Internet, blocking outside traffic that claims to be from within the organization, restricting web requests to the Internet that are not from the internal web proxy server, and limiting information transfers between organizations based on data structures and content. Transferring information between information systems representing different security domains with different security policies introduces risk that such transfers violate one or more domain security policies. In such situations, information owners/stewards provide guidance at designated policy enforcement points between interconnected systems. Organizations consider mandating specific architectural solutions when required to enforce specific security policies. Enforcement includes, for example: (i) prohibiting information transfers between interconnected systems (i.e., allowing access only); (ii) employing hardware mechanisms to enforce one-way information flows; and (iii) implementing trustworthy regrading mechanisms to reassign security attributes and security labels. Organizations commonly employ information flow control policies and enforcement mechanisms to control the flow of information between designated sources and destinations (e.g., networks, individuals, and devices) within information systems and between interconnected systems. Flow control is based on the characteristics of the information and/or the information path. Enforcement occurs, for example, in boundary protection devices (e.g., gateways, routers, guards, encrypted tunnels, firewalls) that employ rule sets or establish configuration settings that restrict information system services, provide a packet-filtering capability based on header information, or message-filtering capability based on message content (e.g., implementing key word searches or using document characteristics). Organizations also consider the trustworthiness of filtering/inspection mechanisms (i.e., hardware, firmware, and software components) that are critical to information flow enforcement. Control enhancements 3 through 22 primarily address cross-domain solution needs which focus on more advanced filtering techniques, in-depth analysis, and stronger flow enforcement mechanisms implemented in cross-domain products, for example, high-assurance guards. Such capabilities are generally not available in commercial off-the-shelf information technology products.





