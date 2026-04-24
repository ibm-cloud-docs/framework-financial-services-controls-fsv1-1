---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
---

{{site.data.keyword.attribute-definition-list}}


# AC-7 - Unsuccessful Logon Attempts [FSv1.1]
{: #ac-7}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The information system:

AC-7 (a)
    : Enforces a limit of _[IBM Assignment: not more than five (5)]_ consecutive invalid logon attempts by a user during a _[IBM Assignment: fifteen (15) minutes]_; and

AC-7 (b)
    : Automatically _[IBM Assignment: locks the account/node for a thirty (30) minutes]_ when the maximum number of unsuccessful attempts is exceeded.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Internal privileged accounts must remain locked until released by an administrator.




## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control applies regardless of whether the logon occurs via a local or network connection. Due to the potential for denial of service, automatic lockouts initiated by information systems are usually temporary and automatically release after a predetermined time period established by organizations. If a delay algorithm is selected, organizations may choose to employ different algorithms for different information system components based on the capabilities of those components. Responses to unsuccessful logon attempts may be implemented at both the operating system and the application levels.
