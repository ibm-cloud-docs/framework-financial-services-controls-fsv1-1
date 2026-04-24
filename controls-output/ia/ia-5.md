---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
---

{{site.data.keyword.attribute-definition-list}}


# IA-5 - Authenticator Management [FSv1.1]
{: #ia-5}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization manages information system authenticators by:

IA-5 (a)
    : Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, or device receiving the authenticator;

IA-5 (b)
    : Establishing initial authenticator content for authenticators defined by the organization;

IA-5 (c)
    : Ensuring that authenticators have sufficient strength of mechanism for their intended use;

IA-5 (d)
    : Establishing and implementing administrative procedures for initial authenticator distribution, for lost/compromised or damaged authenticators, and for revoking authenticators;

IA-5 (e)
    : Changing default content of authenticators prior to information system installation;

IA-5 (f)
    : Establishing minimum and maximum lifetime restrictions and reuse conditions for authenticators;

IA-5 (g)
    : Changing/refreshing authenticators _[IBM Assignment: 90 days for user passwords and 365 days for system-to-system authenticators]_;

IA-5 (h)
    : Protecting authenticator content from unauthorized disclosure and modification;

IA-5 (i)
    : Requiring individuals to take, and having devices implement, specific security safeguards to protect authenticators; and

IA-5 (j)
    : Changing authenticators for group/role accounts when membership to those accounts changes.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)
- [Handling and securing secrets](/docs/framework-financial-services?topic=framework-financial-services-shared-secrets)



## NIST supplemental guidance
{: #nist-supplemental-guidance}

Individual authenticators include, for example, passwords, tokens, biometrics, PKI certificates, and key cards. Initial authenticator content is the actual content (e.g., the initial password) as opposed to requirements about authenticator content (e.g., minimum password length). In many cases, developers ship information system components with factory default authentication credentials to allow for initial installation and configuration. Default authentication credentials are often well known, easily discoverable, and present a significant security risk. The requirement to protect individual authenticators may be implemented via control PL-4 or PS-6 for authenticators in the possession of individuals and by controls AC-3, AC-6, and SC-28 for authenticators stored within organizational information systems (e.g., passwords stored in hashed or encrypted formats, files containing encrypted or hashed passwords accessible with administrator privileges). Information systems support individual authenticator management by organization-defined settings and restrictions for various authenticator characteristics including, for example, minimum password length, password composition, validation time window for time synchronous one-time tokens, and number of allowed rejections during the verification stage of biometric authentication. Specific actions that can be taken to safeguard authenticators include, for example, maintaining possession of individual authenticators, not loaning or sharing individual authenticators with others, and reporting lost, stolen, or compromised authenticators immediately. Authenticator management includes issuing and revoking, when no longer needed, authenticators for temporary access such as that required for remote maintenance. Device authenticators include, for example, certificates and passwords.
