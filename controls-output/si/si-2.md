---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SI-2 - Flaw Remediation [FSv1.1]
{: #si-2}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

SI-2 (a)
    : Identifies, reports, and corrects information system flaws;

SI-2 (b)
    : Tests software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;

SI-2 (c)
    : Installs security-relevant software and firmware updates within _[IBM Assignment: RA-5 (d) timeframes]_ of the release of the updates; and

SI-2 (d)
    : Incorporates flaw remediation into the organizational configuration management process.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization must remediate vulnerability findings in accordance with customer remediation requirements.
- All software/technology is upgraded to the most up to date supported version.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| SI-2 (a) | - Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities \n - Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies \n - Check whether Container Registry Vulnerability Advisor scans for critical or high vulnerabilities in the system at least every # day(s) \n - Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely \n - Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts \n - Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities \n - Check whether DevSecOps Toolchain source code contains no secrets \n - Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code \n - Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts \n - Check whether Event Notifications are configured for each of the supported Service \n - Check whether DevSecOps Toolchain passes unit tests to validate all code changes \n - Check whether DevSecOps Toolchain passes acceptance tests to validate every deployment \n - Check whether DevSecOps Toolchain signs build artifacts to attest their provenance \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| SI-2 (b) | - Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities \n - Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies \n - Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely \n - Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts \n - Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities \n - Check whether DevSecOps Toolchain source code contains no secrets \n - Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code \n - Check whether DevSecOps Toolchain passes unit tests to validate all code changes \n - Check whether DevSecOps Toolchain passes acceptance tests to validate every deployment \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| SI-2 (c) | - Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities \n - Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely \n - Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts \n - Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities \n - Check whether DevSecOps Toolchain source code contains no secrets \n - Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| SI-2 (d) | - Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities \n - Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies \n - Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely \n - Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts \n - Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities \n - Check whether DevSecOps Toolchain source code contains no secrets \n - Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code \n - Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts \n - Check whether DevSecOps Toolchain passes unit tests to validate all code changes \n - Check whether DevSecOps Toolchain passes acceptance tests to validate every deployment \n - Check whether DevSecOps Toolchain signs build artifacts to attest their provenance \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
{: caption="Rules for SI-2 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Organizations identify information systems affected by announced software flaws including potential vulnerabilities resulting from those flaws, and report this information to designated organizational personnel with information security responsibilities. Security-relevant software updates include, for example, patches, service packs, hot fixes, and anti-virus signatures. Organizations also address flaws discovered during security assessments, continuous monitoring, incident response activities, and system error handling. Organizations take advantage of available resources such as the Common Weakness Enumeration (CWE) or Common Vulnerabilities and Exposures (CVE) databases in remediating flaws discovered in organizational information systems. By incorporating flaw remediation into ongoing configuration management processes, required/anticipated remediation actions can be tracked and verified. Flaw remediation actions that can be tracked and verified include, for example, determining whether organizations follow US-CERT guidance and Information Assurance Vulnerability Alerts. Organization-defined time periods for updating security-relevant software and firmware may vary based on a variety of factors including, for example, the security category of the information system or the criticality of the update (i.e., severity of the vulnerability related to the discovered flaw). Some types of flaw remediation may require more testing than other types. Organizations determine the degree and type of testing needed for the specific type of flaw remediation activity under consideration and also the types of changes that are to be configuration-managed. In some situations, organizations may determine that the testing of software and/or firmware updates is not necessary or practical, for example, when implementing simple anti-virus signature updates. Organizations may also consider in testing decisions, whether security-relevant software or firmware updates are obtained from authorized sources with appropriate digital signatures.





