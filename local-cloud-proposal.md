---
permalink: /local-cloud-proposal/
layout: default
title: Civic Cloud for Burlington, Vermont (Proposal)
---

Civic Cloud for Burlington, Vermont
===================================

Proposal

Contribute to this proposal by forking this document on GitHub:  
<https://github.com/codeforbtv>

This work is licensed under the Creative Commons Attribution 3.0 Unported license (<http://creativecommons.org/licenses/by/3.0/>).

Summary
-------

The Civic Cloud Collaborative proposes to colocate a server rack within Burlington Telecom's gigabit network. Using this server rack, the Civic Cloud Collaborative will make cloud computing resources available for non-commercial Internet applications with a focus on public, educational, and government access. With an uplink to Burlington Telecom's gigabit network, the Civic Cloud will provide the infrastructure on which to deploy next-generation Internet applications. The Civic Cloud will be a platform for collaborative innovation while demonstrating the potential of Burlington's gigabit network.

Introduction
------------

Burlington has one of a handful of gigabit networks in the country. These gigabit networks are islands of super-fast connectivity. It is only within (and to some extent between) these networks that the true potential of gigabit can currently be realized. Until the rest of the Internet catches up, the potential of Burlington Telecom's gigabit network can only be realized with applications deployed inside the network.

As a US Ignite Partner, the City of Burlington is looking to showcase next-generation Internet applications that provide transformative public benefit in the areas of education & workforce, energy, health, public safety, transportation, and advanced manufacturing. Applications focused on any of these areas could be hosted in the Civic Cloud. Some examples of gigabit applications to be hosted in the Civic Cloud include:

* **Lakecraft:** educational tool that engages youth and adults in science by gamifying the Lake Champlain Basin
* **School Juice:** application that will present the energy usage data of all area schools in a way that can be searched, accessed by API, and visualized
* **Live Streaming:** gigabit networks would allow for 1080p (or even 4K or 8K) streaming where most existing services are limited to 720p at best

One unique benefit of the Civic Cloud would be in the area of public safety. The Vermont Digital Economy Project has found that communities with digitally connected non-governmental organizations are more resilient after natural disasters such as Tropical Storm Irene. Collaborating with the Vermont Digital Economy Project, volunteers working with Code for BTV, a Code for America Brigade, have built or improved websites for several non-governmental organizations and plan to work on many more of these websites. Having these websites hosted together in the Civic Cloud would allow the Vermont Digital Economy Project to improve security, provide options for disaster response, share content between organizations, and more easily link the organizations together.

Many organizations lost a great deal of data during Tropical Storm Irene including donor lists, photos, and other information critical to their operations. In addition to web hosting, services such as cloud storage and cloud backup could be provided in the Civic Cloud. Cloud hosting, cloud storage, and cloud backup services available to Vermont’s non-governmental organizations (and possibly local governments) would make Vermont a leader in resilience to natural disasters.

Approach
--------

![cloud computing layers](http://upload.wikimedia.org/wikipedia/commons/3/3c/Cloud_computing_layers.png "cloud computing layers")

Initially, the Civic Cloud will provide virtual servers that are manually provisioned. Later, the Civic Cloud will provide an Infrastructure as a Service (IaaS) cloud computing resource. This layer will most likely be managed by OpenStack, an open source software project backed by more than 200 companies. This approach will make it technically possible to run almost any application in the Civic Cloud. 

In the future, the Civic Cloud may also host a Platform as a Service (PaaS) layer. The PaaS layer would most likely be managed by OpenShift Origin. This would make it easier to deploy applications written in common programming languages such as Node.js, Ruby, Python, PHP, Perl, or Java. OpenShift Origin also supports several common databases including MySQL, PostgreSQL, and MongoDB.

The IaaS and PaaS layers will allow developers to deploy Software as a Service (SaaS) applications in the Civic Cloud. When the average person uses the word "cloud" they are typically referring to the SaaS layer of the cloud. A wide variety of innovative SaaS applications could be hosted in the Civic Cloud with direct access to Burlington Telecom's gigabit network.

### Plan

The Civic Cloud Collaborative will break its work into three phases. Phase 1 (pilot) will be made possible by volunteers, equipment donations, and service donations. Phase 2 (implement) will involve seed money to compensate for the staff time of contributing organizations and any additional capital expenses. Phase 3 (sustain) will focus on finding sustainable funding sources and defining the governance structure for the Civic Cloud Collaborative.

#### Phase 1: Pilot

This phase will be bootstrapped by volunteers and donations. The following physical infrastructure will be required (a check indicates this equipment has already been procured):

* \[x\] 1x rack enclosure (42U; 79" x 25" x 40")
* \[x\] 1x power distribution unit (PDU)
* \[x\] 1x firewall w/ 3x gigabit NICs
* \[x\] 2x managed L2/L3 8 port gigabit switch
* \[x\] 3x servers

During phase 1:

* Virtual servers will be manually provisioned using an OpenStack compatible KVM hypervisor, but there will be no IaaS layer
* Only non-critical applications will be deployed
* No email applications will be allowed (e.g. SMTP, CRM, mailing lists)

Specific applications targeted for deployment in phase 1 include:

* Live streaming for public, educational, and government access
* WordPress Multisite for statewide verticals (e.g. rescue squads, food shelves, job banks, historical societies)
* Lakecraft

#### Phase 2: Implement

While phase 1 will be bootstrapped, phase 2 will involve finding seed money to cover the buildout of the Infrastructure as a Service (IaaS) layer and ongoing expenses for a limited period of time.

During phase 2:

* An internal storage area network (SAN) will be added
* An Infrastructure as a Service (IaaS) layer will be added, but there will be no PaaS layer
* Components will be standardized and technical oversight processes will be developed
* Service continuity will be an area of priority

Phase 2 will involve more public facing activities including:

* Additional public, educational, and government applications deployed
* Outreach to organizations and individuals who could use the Civic Cloud
* Organic expansion of services based on community needs

#### Phase 3: Sustain

The main goal of phase 3 will be to develop a plan for the long term sustainability of the Civic Cloud. This will include finding sustainable funding sources, defining the governance structure, and defining the identity for the Civic Cloud Collaborative moving forward. Phase 3 may also include acquiring funds to buildout a Platform as a Service (PaaS) layer.

During phase 3:

* Additional capacity will be added to the internal storage area network (SAN)
* Additional servers will be added to the Civic Cloud, expanding its capacity
* Over time, old servers will be replaced with new servers
* A Platform as a Service (PaaS) layer may be added, making it easier for developers to deploy applications written in common programming languages
* Opportunities for software-defined networking (SDN) will be explored

Phase 1 Requirements
--------------------

The following will be required from Burlington Telecom in order to make the Civic Cloud possible:

* Physical space for a rack enclosure (42U; 79" x 25" x 40")
* Electricity with battery backup and generator (16A @ 110V, est.)
* Air conditioning (6,000 BTU/h, est.)
* Gigabit uplink (1000BASE-T) to internal network
* IPv4 address block (approx. 20 hosts) 

The Civic Cloud Collaborative will work with Burlington Telecom to establish regularly scheduled maintenance windows during which physical access will be provided to the rack enclosure. The Civic Cloud Collaborative will designate a technical contact with whom Burlington Telecom will communicate in regards to any technical matters.

We also ask that Burlington Telecom provide gigabit service at a nominal cost to non-commercial technical collaborators. This will provide an immediate, if small, test bed for gigabit applications hosted within the Civic Cloud.

About the Civic Cloud Collaborative
-----------------------------------

The Civic Cloud Collaborative is comprised of Big Heavy World, CCTV Center for Media & Democracy, Code for BTV, Found Line, and Laboratory B. This document is a proposal for the Civic Cloud Collaborative to partner with Burlington Telecom, the City of Burlington, and US Ignite to develop the Civic Cloud.

Potential Collaborators
-----------------------

* BTV Gig
* Fletcher Free Library
* RETN
* VCAM
* Vermont Digital Economy Project
* Vermont Resilience Lab
