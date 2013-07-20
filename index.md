---
layout: default
title: Local Cloud for Burlington, Vermont
---

Local Cloud for Burlington, Vermont
===================================

Strategic Plan

Contribute to this strategic plan by forking this document on GitHub:  
<https://github.com/codeforbtv>

Vision
------

Burlington has its own gigabit network that passes between 85% and 90% of the addresses in the city. In partnership with US Ignite, Burlington's gigabit network is a test bed for "[fostering] the creation of next-generation Internet applications that provide transformative public benefit."

Many of today's Internet applications are hosted in cloud computing environments. Cloud computing is a utility model that reduces costs by sharing resources and leveraging economies of scale. Many next-generation Internet applications will continue to choose the cloud computing model.

There are only a handful of gigabit networks throughout the country. Given the state of our Internet infrastructure at the national level, these gigabit networks are islands of super-fast connectivity. It is only within (and to some extent between) these networks that the true potential of gigabit can currently be realized.

Values
------

The local cloud initiative is being facilitated by Code for BTV, a Code for America Brigade, as well as community media organizations in Burlington. Both CCTV Center for Media & Democracy and Big Heavy World have discussed providing resources to this initiative. Code for BTV values participatory government and civic engagement. CCTV Center for Media & Democracy values free speech, public access, and open networks. Big Heavy World values the potential of Vermont's youth, self-worth, diversity, positivity, civic participation, independent thought, and community. All involved in this initiative value digital inclusion. Digital inclusion is social inclusion for the digital age, a proactive effort to mitigate the causes of social exclusion.

Mission
-------

The local cloud initiative will provide cloud computing resources for Internet applications that benefit the common good. While next-generation Internet applications are a natural fit, any public interest Internet application would be eligible to use the local cloud. The local cloud will provide access to the gigabit network, in the form of application hosting, to those who might not otherwise have access.

Strategy
--------

The local cloud initiative aims to colocate a server rack within Burlington Telecom's network operations center. This would place the local cloud within the core of Burlington's gigabit network. This approach has several advantages:

* Redundant infrastructure (battery backup, dedicated generator, air conditioning)
* Higher throughput
* Lower latency

To make colocation practical, Burlington Telecom will likely need to limit physical access to the server rack. Redundant hardware and virtualization of computing resources can make it possible to limit physical access to scheduled maintenance windows. An agreement on emergency maintenance should be reached, but the infrastructure should be designed to avoid emergency maintenance as much as possible.

![cloud computing layers](http://upload.wikimedia.org/wikipedia/commons/3/3c/Cloud_computing_layers.png "cloud computing layers")

Infrastructure as a Service (IaaS), the basic building block of cloud computing, will be the first cloud computing resource provided by the local cloud. This will be a set of virtual machines running on top of the physical hardware. Lakecraft, a Code for BTV project, could be a pilot application run on the IaaS layer.

On top of the IaaS layer, one or more Platform as a Service (PaaS) offerings could be provided. Web hosting would be one example of a PaaS, but there are much more sophisticated forms of PaaS as well. A basic Linux, Apache, MySQL, and PHP (LAMP) PaaS could be provided to the Vermont Digital Economy Project for non-governmental organization web hosting.

Multiple Software as a Service (SaaS) applications could be hosted on top of each PaaS layer. SaaS is the part of the cloud with which most end users interact. WordPress multisite installs could be provided by Code for BTV and the Vermont Digital Economy Project to non-governmental organization "verticals" (e.g. rescue squads, food shelfs, job banks). A food shelf, for example, in need of a new website could have this website provisioned as part of the WordPress food shelf multisite install. Each WordPress multisite install (SaaS) would be installed on top of the LAMP PaaS which would itself be running on the IaaS layer.

While the local cloud initiative is focused on next-generation connectivity, local clouds could also be colocated at the core of other networks. For example, Comcast or FairPoint could provide a server rack for a local cloud within their networks. A local cloud would still have value, even on non-gigabit networks.
