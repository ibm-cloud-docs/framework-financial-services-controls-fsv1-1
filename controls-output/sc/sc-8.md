---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
---

{{site.data.keyword.attribute-definition-list}}


# SC-8 - Transmission Confidentiality and Integrity [FSv1.1]
{: #sc-8}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

SC-8 - 0
    : The information system protects the [IBM Assignment: confidentiality, integrity, AND availability] of transmitted information.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)
- [Data encryption in transit](/docs/framework-financial-services?topic=framework-financial-services-shared-encryption-in-transit)
- [Working with {{site.data.keyword.openshiftlong_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-containers-openshift)



## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control applies to both internal and external networks and all types of information system components from which information can be transmitted (e.g., servers, mobile devices, notebook computers, printers, copiers, scanners, facsimile machines). Communication paths outside the physical protection of a controlled boundary are exposed to the possibility of interception and modification. Protecting the confidentiality and/or integrity of organizational information can be accomplished by physical means (e.g., by employing protected distribution systems) or by logical means (e.g., employing encryption techniques). Organizations relying on commercial providers offering transmission services as commodity services rather than as fully dedicated services (i.e., services which can be highly specialized to individual customer needs), may find it difficult to obtain the necessary assurances regarding the implementation of needed security controls for transmission confidentiality/integrity. In such situations, organizations determine what types of confidentiality/integrity services are available in standard, commercial telecommunication service packages. If it is infeasible or impractical to obtain the necessary security controls and assurances of control effectiveness through appropriate contracting vehicles, organizations implement appropriate compensating security controls or explicitly accept the additional risk.
