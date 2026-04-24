---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
---

{{site.data.keyword.attribute-definition-list}}


# CM-4 (1) - Separate Test Environments [FSv1.1]
{: #cm-4.1}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

CM-4 (1) - 0
    : The organization analyzes changes to the information system in a separate test environment before implementation in an operational environment, looking for security impacts due to flaws, weaknesses, incompatibility, or intentional malice.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The test environment must mirror the production environment.
- Customer data must not be placed into non-production environments.




## NIST supplemental guidance
{: #nist-supplemental-guidance}

Separate test environment in this context means an environment that is physically or logically isolated and distinct from the operational environment. The separation is sufficient to ensure that activities in the test environment do not impact activities in the operational environment, and information in the operational environment is not inadvertently transmitted to the test environment. Separate environments can be achieved by physical or logical means. If physically separate test environments are not used, organizations determine the strength of mechanism required when implementing logical separation (e.g., separation achieved through virtual machines).
