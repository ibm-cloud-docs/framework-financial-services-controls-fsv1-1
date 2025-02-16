---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# MA-4 - Nonlocal Maintenance [FSv1.1]
{: #ma-4}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

MA-4 (a)
    : Approves and monitors nonlocal maintenance and diagnostic activities;

MA-4 (b)
    : Allows the use of nonlocal maintenance and diagnostic tools only as consistent with organizational policy and documented in the security plan for the information system;

MA-4 (c)
    : Employs strong authenticators in the establishment of nonlocal maintenance and diagnostic sessions;

MA-4 (d)
    : Maintains records for nonlocal maintenance and diagnostic activities; and

MA-4 (e)
    : Terminates session and network connections when nonlocal maintenance is completed.

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Nonlocal maintenance and diagnostic activities are those activities conducted by individuals communicating through a network, either an external network (e.g., the Internet) or an internal network. Local maintenance and diagnostic activities are those activities carried out by individuals physically present at the information system or information system component and not communicating across a network connection. Authentication techniques used in the establishment of nonlocal maintenance and diagnostic sessions reflect the network access requirements in IA-2. Typically, strong authentication requires authenticators that are resistant to replay attacks and employ multifactor authentication. Strong authenticators include, for example, PKI where certificates are stored on a token protected by a password, passphrase, or biometric. Enforcing requirements in MA-4 is accomplished in part by other controls.





