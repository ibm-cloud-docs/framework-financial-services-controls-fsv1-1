---

copyright:
  years: 2020, 2026

lastupdated: "2026-04-24"

keywords:

subcollection: framework-financial-services-controls-fsv1-1
---

{{site.data.keyword.attribute-definition-list}}


# CM-7 - Least Functionality [FSv1.1]
{: #cm-7}

This control is based on IBM Cloud Framework for Financial Services v1.1.
{: note}


## Control requirements
{: #control-requirements}

The organization:

CM-7 (a)
    : Configures the information system to provide only essential capabilities; and

CM-7 (b)
    : Prohibits or restricts the use of the following functions, ports, protocols, and/or services: _[IBM Assignment: limiting, disabling, and/or controlling services, features, applications, functions, ports, and protocols not explicitly required to support business functionality]_.



## NIST supplemental guidance
{: #nist-supplemental-guidance}

Information systems can provide a wide variety of functions and services. Some of the functions and services, provided by default, may not be necessary to support essential organizational operations (e.g., key missions, functions). Additionally, it is sometimes convenient to provide multiple services from single information system components, but doing so increases risk over limiting the services provided by any one component. Where feasible, organizations limit component functionality to a single function per device (e.g., email servers or web servers, but not both). Organizations review functions and services provided by information systems or individual components of information systems, to determine which functions and services are candidates for elimination (e.g., Voice Over Internet Protocol, Instant Messaging, auto-execute, and file sharing). Organizations consider disabling unused or unnecessary physical and logical ports/protocols (e.g., Universal Serial Bus, File Transfer Protocol, and Hyper Text Transfer Protocol) on information systems to prevent unauthorized connection of devices, unauthorized transfer of information, or unauthorized tunneling. Organizations can utilize network scanning tools, intrusion detection and prevention systems, and end-point protections such as firewalls and host-based intrusion detection systems to identify and prevent the use of prohibited functions, ports, protocols, and services.
