---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
---

{{site.data.keyword.attribute-definition-list}}


# CM-6 - Configuration Settings [FSv1.1]
{: #cm-6}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

CM-6 (a)
    : Establishes and documents configuration settings for information technology products employed within the information system using _[IBM Assignment: see CM-6 (a) Additional Requirements and Guidance]_ that reflect the most restrictive mode consistent with operational requirements;

CM-6 (b)
    : Implements the configuration settings;

CM-6 (c)
    : Identifies, documents, and approves any deviations from established configuration settings for _[Assignment: organization-defined information system components]_ based on _[Assignment: organization-defined operational requirements]_; and

CM-6 (d)
    : Monitors and controls changes to the configuration settings in accordance with organizational policies and procedures.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Usage and configuration changes made to Virtual Machine Monitors (VMM) and hypervisors must be documented and maintained for customer review.
- NIST SP 800-125A Security Recommendations for Server-based Hypervisor Platforms should be consulted for additional guidance.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Compliance monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-compliance)



## NIST supplemental guidance
{: #nist-supplemental-guidance}

Configuration settings are the set of parameters that can be changed in hardware, software, or firmware components of the information system that affect the security posture and/or functionality of the system. Information technology products for which security-related configuration settings can be defined include, for example, mainframe computers, servers (e.g., database, electronic mail, authentication, web, proxy, file, domain name), workstations, input/output devices (e.g., scanners, copiers, and printers), network components (e.g., firewalls, routers, gateways, voice and data switches, wireless access points, network appliances, sensors), operating systems, middleware, and applications. Security-related parameters are those parameters impacting the security state of information systems including the parameters required to satisfy other security control requirements. Security-related parameters include, for example: (i) registry settings; (ii) account, file, directory permission settings; and (iii) settings for functions, ports, protocols, services, and remote connections. Organizations establish organization-wide configuration settings and subsequently derive specific settings for information systems. The established settings become part of the systems configuration baseline. Common secure configurations (also referred to as security configuration checklists, lockdown and hardening guides, security reference guides, security technical implementation guides) provide recognized, standardized, and established benchmarks that stipulate secure configuration settings for specific information technology platforms/products and instructions for configuring those information system components to meet operational requirements. Common secure configurations can be developed by a variety of organizations including, for example, information technology product developers, manufacturers, vendors, consortia, academia, industry, federal agencies, and other organizations in the public and private sectors. Common secure configurations include the United States Government Configuration Baseline (USGCB) which affects the implementation of CM-6 and other controls such as AC-19 and CM-7. The Security Content Automation Protocol (SCAP) and the defined standards within the protocol (e.g., Common Configuration Enumeration) provide an effective method to uniquely identify, track, and control configuration settings. OMB establishes federal policy on configuration requirements for federal information systems.
