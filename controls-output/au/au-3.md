---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AU-3 - Content of Audit Records [FSv1.1]
{: #au-3}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

AU-3 - 0
    : The information system generates audit records containing information that establishes what type of event occurred, when the event occurred, where the event occurred, the source of the event, the outcome of the event, and the identity of any individuals or subjects associated with the event.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The following events are to be audited within the system:
- The identity of the account accessing the system, e.g., standard accounts, secondary accounts, external accounts, service accounts.
- Date and local time zone (or UTC)
- Authentication method, examples include but are not limited to SSO, mainframe, etc.
- System name generating the log
- Log recording system name
- Source IP address
- Port, where available
- Protocol, where available
- Session duration, where available
- Session Identification, where available
- Cookie session identification value modification, where available

In some cases, legal, compliance or business reasons may result in the need for additional security audit logging attributes for a given system. Please refer to the customer for more information/requirements.

Validate audit/log files contain the necessary information the customer requires to meet policy/regulatory requirements.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)
- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check that Activity Tracker Event Routing is configured to collect global events generated by IBM Cloud services

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Audit record content that may be necessary to satisfy the requirement of this control, includes, for example, time stamps, source and destination addresses, user/process identifiers, event descriptions, success/fail indications, filenames involved, and access control or flow control rules invoked. Event outcomes can include indicators of event success or failure and event-specific results (e.g., the security state of the information system after the event occurred).





