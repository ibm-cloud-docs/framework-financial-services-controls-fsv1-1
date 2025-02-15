---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CP-2 - Contingency Plan [FSv1.1]
{: #cp-2}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

CP-2 (a)
    : Develops a contingency plan for the information system that:
      1. Identifies essential missions and business functions and associated contingency requirements;
      2. Provides recovery objectives, restoration priorities, and metrics;
      3. Addresses contingency roles, responsibilities, assigned individuals with contact information;
      4. Addresses maintaining essential missions and business functions despite an information system disruption, compromise, or failure;
      5. Addresses eventual, full information system restoration without deterioration of the security safeguards originally planned and implemented; and
      6. Is reviewed and approved by _[IBM Assignment: designated senior management personnel who is not an author or contributor to the plan]_;

CP-2 (b)
    : Distributes copies of the contingency plan to _[Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements]_;

CP-2 (c)
    : Coordinates contingency planning activities with incident handling activities;

CP-2 (d)
    : Reviews the contingency plan for the information system _[IBM Assignment: annually or within 90 calendar days of significant changes]_;

CP-2 (e)
    : Updates the contingency plan to address changes to the organization, information system, or environment of operation and problems encountered during contingency plan implementation, execution, or testing;

CP-2 (f)
    : Communicates contingency plan changes to _[Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements]_; and

CP-2 (g)
    : Protects the contingency plan from unauthorized disclosure and modification.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Documentation includes plan and playbook(s).
- The organization must provide required pre-test documentation prior to test initiation. The customer must provide the organization with what is included in pre-test documentation.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)
- [High availability overview](/docs/framework-financial-services?topic=framework-financial-services-shared-high-availability)

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Contingency planning for information systems is part of an overall organizational program for achieving continuity of operations for mission/business functions. Contingency planning addresses both information system restoration and implementation of alternative mission/business processes when systems are compromised. The effectiveness of contingency planning is maximized by considering such planning throughout the phases of the system development life cycle. Performing contingency planning on hardware, software, and firmware development can be an effective means of achieving information system resiliency. Contingency plans reflect the degree of restoration required for organizational information systems since not all systems may need to fully recover to achieve the level of continuity of operations desired. Information system recovery objectives reflect applicable laws, Executive Orders, directives, policies, standards, regulations, and guidelines. In addition to information system availability, contingency plans also address other security-related events resulting in a reduction in mission and/or business effectiveness, such as malicious attacks compromising the confidentiality or integrity of information systems. Actions addressed in contingency plans include, for example, orderly/graceful degradation, information system shutdown, fallback to a manual mode, alternate information flows, and operating in modes reserved for when systems are under attack. By closely coordinating contingency planning with incident handling activities, organizations can ensure that the necessary contingency planning activities are in place and activated in the event of a security incident.





