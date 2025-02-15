---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-15"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CM-8 (3) - Automated Unauthorized Component Detection [FSv1.1]
{: #cm-8.3}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

CM-8 (3) (a)
    : Employs automated mechanisms _[IBM Assignment: Continuously, using automated mechanisms with a maximum five-minute delay in detection]_ to detect the presence of unauthorized hardware, software, and firmware components within the information system; and

CM-8 (3) (b)
    : Takes the following actions when unauthorized components are detected: _[Selection (one or more): disables network access by such components; isolates the components; notifies [Assignment: organization-defined personnel or roles]_ ].

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control enhancement is applied in addition to the monitoring for unauthorized remote connections and mobile devices. Monitoring for unauthorized system components may be accomplished on an ongoing basis or by the periodic scanning of systems for that purpose. Automated mechanisms can be implemented within information systems or in other separate devices. Isolation can be achieved, for example, by placing unauthorized information system components in separate domains or subnets or otherwise quarantining such components. This type of component isolation is commonly referred to as sandboxing.





