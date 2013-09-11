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

As a US Ignite Partner, the City of Burlington is looking to showcase next-generation Internet applications that provide transformative public benefit in the areas of education & workforce, energy, health, public safety, transportation, and advanced manufacturing. Applications focused on any of these areas could be hosted in the Civic Cloud.

One unique benefit of the Civic Cloud would be in the area of public safety. The Vermont Digital Economy Project has found that communities with digitally connected non-governmental organizations are more resilient after natural disasters such as Tropical Storm Irene. Collaborating with the Vermont Digital Economy Project, volunteers working with Code for BTV, a Code for America Brigade, have built or improved websites for several non-governmental organizations and plan to work on many more of these websites. Hosting these websites in the Civic Cloud would help make the communities served by these non-governmental organizations more resilient to natural disasters.

Many organizations lost a great deal of data during Tropical Storm Irene including donor lists, photos, and other information critical to their operations. In addition to web hosting, services such as cloud storage and cloud backup could be provided in the Civic Cloud. Cloud hosting, cloud storage, and cloud backup services available to Vermont’s non-governmental organizations (and possibly local governments) would make Vermont a leader in resilience to natural disasters.

Approach
--------

![cloud computing layers](http://upload.wikimedia.org/wikipedia/commons/3/3c/Cloud_computing_layers.png "cloud computing layers")

Initially, the Civic Cloud will provide virtual servers that are manually provisioned. Later, the Civic Cloud will provide an Infrastructure as a Service (IaaS) cloud computing resource. The IaaS layer will most likely be managed by OpenStack, an open source software project backed by more than 200 companies. This approach will make it technically possible to run almost any application in the Civic Cloud. 

In the future, the Civic Cloud may also host a Platform as a Service (PaaS) layer. The PaaS layer would most likely be managed by OpenShift Origin. This would make it easier to deploy applications written in common programming languages such as Node.js, Ruby, Python, PHP, Perl, or Java. OpenShift Origin also supports several common databases including MySQL, PostgreSQL, and MongoDB.

The IaaS and PaaS layers will allow developers to deploy Software as a Service (SaaS) applications in the Civic Cloud. When the average person uses the word "cloud" they are typically referring to the SaaS layer of the cloud. A wide variety of innovative SaaS applications could be hosted in the Civic Cloud with direct access to Burlington Telecom's gigabit network.

### Plan

The Civic Cloud Collaborative will break its work into three phases. Phase 1 (pilot) will be made possible by volunteers, equipment donations, and service donations. Phase 2 (implement) will involve seed money to compensate for the staff time of contributing organizations and any additional capital expenses. Phase 3 (sustain) will focus on finding sustainable funding sources and defining the governance structure for the Civic Cloud Collaborative.

While there are no set timelines, the Civic Cloud Collaborative would begin phase 1 with the goal of ultimately completing phase 3. While phase 1 has some limited value to the community, its main value is as a stepping stone to phase 2. Phase 2 will start to deliver significant value to the community. Phase 3 will ensure that this value can be sustained and expanded.

#### Phase 1: Pilot

This phase will be bootstrapped by volunteers and donations. All of the physical infrastructure necessary for phase 1 has been acquired by the Civic Cloud Collaborative. This includes:

* 1x rack enclosure (42U; 79" x 25" x 40")
* 1x power distribution unit (PDU)
* 1x firewall w/ 3x gigabit NICs
* 2x managed L2/L3 8 port gigabit switch
* 6x servers

During phase 1:

* Virtual servers will be manually provisioned using an OpenStack compatible KVM hypervisor, but there will be no IaaS layer
* Only non-critical applications will be deployed
* No email applications will be allowed (e.g. SMTP, CRM, mailing lists)

Applications targeted for deployment in phase 1 include:

* Live streaming for community media, including community radio as well as public, educational, and government access
* WordPress Multisite for statewide non-commercial verticals (e.g. rescue squads, food shelves, job banks, historical societies)
* Big Heavy World: A collection of applications that help preserve and promote Vermont-made music
* Lakecraft: an educational tool that engages youth and adults in science by gamifying the Lake Champlain Basin

The estimated budget for phase 1 is $26,100. This includes the physical infrastructure and labor costs. As noted, all of the physical infrastructure for phase 1 has been procured. Hundreds of skilled person-hours have been committed by volunteers and members of the Civic Cloud Collaborative to complete phase 1.

#### Phase 2: Implement

While phase 1 will be bootstrapped, phase 2 will involve finding seed money to cover the buildout of the Infrastructure as a Service (IaaS) layer and ongoing expenses for a limited period of time.

During phase 2:

* Remote management will be enabled
* A storage cluster will be added
* An Infrastructure as a Service (IaaS) layer will be added, but there will be no PaaS layer
* Components will be standardized and technical oversight processes will be developed
* Service continuity will be an area of priority

Phase 2 will involve more public facing activities including:

* Additional public, educational, and government applications deployed
* Outreach to organizations and individuals who could use the Civic Cloud
* Organic expansion of services based on community needs

The estimated budget for phase 2 is $49,400.

#### Phase 3: Sustain

The main goal of phase 3 will be to develop a plan for the long term sustainability of the Civic Cloud. This will include finding sustainable funding sources, defining the governance structure, and defining the identity for the Civic Cloud Collaborative moving forward. Phase 3 may also include acquiring funds to buildout a Platform as a Service (PaaS) layer.

During phase 3:

* Additional capacity will be added to the storage cluster
* Additional servers will be added to the Civic Cloud, expanding its capacity
* Over time, old servers will be replaced with new servers
* A Platform as a Service (PaaS) layer may be added, making it easier for developers to deploy applications written in common programming languages
* Opportunities for software-defined networking (SDN) will be explored

The estimated budget for the first year of phase 3 is $138,060.

Phase 1 Requirements
--------------------

The following will be required from Burlington Telecom in order to make the Civic Cloud possible:

* Physical space for a rack enclosure (42U; 79" x 25" x 40")
* Electricity with battery backup and generator (16A @ 110V, est.)
* Air conditioning (6,000 BTU/h, est.)
* Gigabit uplink (1000BASE-T) to internal network
* IPv4 address block (approx. 20 hosts) 

The Civic Cloud Collaborative will work with Burlington Telecom to establish regularly scheduled maintenance windows during which physical access will be provided to the rack enclosure. The Civic Cloud Collaborative will designate a technical contact with whom Burlington Telecom will communicate in regards to any technical matters.

We also ask that Burlington Telecom provide gigabit service at a nominal cost to **non-commercial** technical collaborators. This will provide an immediate, if small, test bed for gigabit applications hosted within the Civic Cloud.

About the Civic Cloud Collaborative
-----------------------------------

The Civic Cloud Collaborative is comprised of Big Heavy World, CCTV Center for Media & Democracy, Channel 17 / Town Meeting Television, Code for BTV (a Code for America Brigade), Found Line, Laboratory B, Regional Educational Technology Network (RETN), and Vermont Community Access Media (VCAM). This document is a proposal for the Civic Cloud Collaborative to partner with Burlington Telecom, the City of Burlington, and US Ignite to develop the Civic Cloud.

Next Steps
----------

The Civic Cloud Collaborative is asking the City of Burlington to fund the costs incurred by Burlington Telecom for the infrastructure needed by the Civic Cloud. This includes physical space, electricity, air conditioning, bandwidth, and an IPv4 address block. The Civic Cloud Collaborative has procured all of the equipment and labor necessary for phase 1 of the Civic Cloud, with an estimated value of $26,100. The costs to the City of Burlington will be minimal relative to the Civic Cloud Collaborative total budget of $213,560 for phase 1, phase 2, and year one of phase 3.

As more servers are added to the Civic Cloud in phase 2 and phase 3 there could be a cost increase to Burlington Telecom. No additional physical space should be needed (the server rack has room for growth). However, the electricity and air conditioning needs could increase as more servers are added. Bandwidth needs could increase as more applications are added (this is likely to be offset by decreasing bandwidth costs). More applications could also increase the number of IPv4 hosts needed. Once a cost baseline is established in phase 1, any additional phase 2 and/or phase 3 costs should be predictable and manageable.

The next steps needed to develop the Civic Cloud include:

1. Burlington Telecom reviews the phase 1 requirements outlined in this document
2. The Civic Cloud Collaborative works with Burlington Telecom to adjust these requirements as needed
3. The City of Burlington approves Burlington Telecom providing the phase 1 requirements to the Civic Cloud Collaborative

Once these steps are completed, the technical contact for the Civic Cloud Collaborative will schedule install times with Burlington Telecom for the Civic Cloud physical infrastructure. The installation of the physical infrastructure will likely take at least two or three visits. The installation will involve placing the server rack itself, preparing the server rack, and installing the servers.

Community Benefit
-----------------

If the City of Burlington wants to become a regional technology center, then the Civic Cloud can be a key component to this strategy. Leveraging Burlington's gigabit network, the Civic Cloud would provide a platform for collaboration, innovation, and experimentation on next-generation Internet applications within Burlington. While the gigabit Internet may currently stop at Burlington's borders, many of the applications hosted in the Civic Cloud would provide community benefit beyond the city limits. With the Civic Cloud being physically located here, the City of Burlington would get credit throughout Vermont (and beyond) for the value it provides to other communities. The Civic Cloud Collaborative plans to document as much of its work as possible, enabling other communities to develop their own Civic Clouds while looking to Burlington as a leader.

While other communities are attempting similar initiatives, the Civic Cloud in Burlington would be unique. Philadelphia is working to create the Philly Public Cloud which "will utilize OpenStack together with community-contributed hardware, rackspace, and management to provide free hosting for public-service apps and sites." However, Philadelphia's cloud will not be on a gigabit network. The University of Maine at Orono is working on a cloud computing project for their gigabit network. The Orono project seems more geared towards researchers, while the goal of the Civic Cloud in Burlington is to be a resource for the entire community.

Civic Cloud Applications
------------------------

Like roads, bridges, the water system, the electric grid, and our city's fiber-optic network, the Civic Cloud will become a part of the civic infrastructure on which our community is built. Hundreds of applications could be hosted in the Civic Cloud as an ecosystem of civic applications are developed. These applications, and the Civic Cloud itself, will serve the civic sector through the development of the social economy.

Following are some examples of applications that could be hosted in the Civic Cloud. Many of these applications are being developed through Code for BTV, a Code for America Brigade. Launched during the National Day of Civic Hacking, Code for BTV is facilitating sustainable collaborations on civic software and open data projects between coders, designers, and organizations (both governmental and non-governmental). Code for BTV will continue to be a source of civic applications that could be hosted in the Civic Cloud.

### Lakecraft

Lakecraft, a Code for BTV project, is an educational tool that engages youth and adults in science by gamifying the Lake Champlain Basin. Using a custom modification to Minecraft, the goal is to eventually have a tool that may be used at the ECHO Center, at home, by educational institutions, and as a model to educators.

### School Juice

School Juice is a team of Code for BTV volunteers brainstorming ways to begin providing electricity usage data from Burlington’s new smart meters in some useful and open ways to the public. This information could be used by the public, by students and by the city to assess progress along the city’s energy reduction goals. The concept is to present the energy usage data of all area schools in a way that can be searched, accessed by API and visualized.

### Live Streaming

While there are existing live streaming services such as Livestream and Ustream, there are benefits to providing a non-commercial version of these services focused on public, educational, and government access. There are free speech implications to relying on a for-profit organization for live streaming, or any other Internet application. The terms of service may limit legitimate uses or the company may decide, for whatever reason, not to carry certain content. Privacy concerns may also have a chilling effect on free speech. Viewers should not have to subject themselves to giving up their data and their privacy in order to watch a live broadcast. Additionally, Burlington's gigabit network would provide for 1080p (or even 4K or 8K) streaming where most services are limited to 720p at best.

### Green Up Vermont

During Green Up Vermont, many inefficiencies were identified: people covering the same ground multiples times, people not knowing where high need was, and people not knowing where to drop off their garbage. A group of Code for BTV volunteers created a web-based mobile user interface with server-side service to collect data points as well as to provide forums for discussion. A client-side data system allows for the organization of data points.

### Live Music Venue Directory

The Big Heavy World Live Music Venue Directory is a tool for Vermont-based and touring artists to orient themselves to the opportunities to perform in Vermont. It helps artists identify appropriate venues and provides the information needed to communicate with them. Not every music venue is a good match with every artist or band. For example, the venue might be too big or small, or have programming interests that don't fit the artist's style of music.

### Discussion Forum

Big Heavy World Discussion Forum is a place for Vermont musicians to connect. Musicians can talk about many genres of music, swap equipment, and find ride sharing opportunities. A previous forum had been overrun by spam bots. This new forum was set up by Code for BTV volunteers during the National Day of Civic Hacking.

### Interactive Event Calendar

Big Heavy World aims to have its music events calendar integrate with the State of Vermont's event calendar. The ultimate goal is to create an interface that is "skinnable" and to make it available as a tool for other arts nonprofits in Vermont to use, allowing them to engage their local communities with the larger pool of information aggregated by the state.

### Vermont Artist Directory

The Vermont Artist Directory is intended for use by the public, venues, and artists to identify and connect with bands or performers for weddings, club shows, or gig swaps/special projects. It should have enough content, including music and photographs, to give a clear idea of what kind of music the artist plays and to make them accessible to anyone through the Big Heavy World site. It's an overview of Vermont's music community, should be searchable by genre or geographic region, and should connect with a band's social network sites.

### Fish Stocking Schedule

Created during the National Day of Civic Hacking, the Fish Stocking Schedule is an application that takes fish stocking data published by Vermont Fish & Wildlife and transforms it into an interactive map. The data can be navigated by number of fish, species, town, average size, body of water, age of fish, and date stocked.

### Burlington City Wiki

A team of Code for BTV volunteers has created a wiki designed to crowdsource information about Burlington. The wiki uses the MediaWiki platform and includes categories and a sampling of content. Importing and supporting extensions are in place (e.g., anti-spam, social networking). The team is looking to recruit writers and editors for the wiki.

### Adopt-a-Drain

Adopt-a-Drain allows individuals to claim responsibility for reporting problems with storm drains. This open source application started as Adopt-a-Hydrant, a tool that lets individuals "adopt" civic infrastructure such as fire hydrants. Individuals would claim responsibility for shoveling out a fire hydrant after it snows. The same application was later adapted as Adopt-a-Sidewalk in Chicago, and Adopt-a-Siren in Honolulu for people to listen during tsunami alert siren tests and report any problems. OpenOakland, a Code for America Brigade, then created Adopt-a-Drain based on this application. The City of Burlington's stormwater program has expressed interest in having an Adopt-a-Drain instance installed for Burlington.

### Cloud Hosting, Cloud Storage, and Cloud Backup

Code for BTV and the Vermont Digital Economy Project would maintain several WordPress Multisite installs, each for a separate non-governmental organization "vertical." Rescue squads, food shelves, job banks, and historical societies could each have their own WordPress Multisite install. A food shelf, for example, in need of a new website could have this website provisioned as part of the food shelf WordPress Multisite install. WordPress Multisite would make the websites much easier to create and maintain. Having all of the websites hosted together would allow the Vermont Digital Economy Project to improve security, provide options for disaster response, share content between organizations, and more easily link the organizations together. This service could be extended to cloud storage and cloud backup available to Vermont’s non-governmental organizations (and possibly local governments).

Potential Collaborators
-----------------------

* BTV Gig
* Fletcher Free Library
* Vermont Digital Economy Project
* Vermont Resilience Lab
