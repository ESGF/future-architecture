---
layout: post
title: "Container-based development - current status"
date: 2020-08-28
---

Work has focused on creating a complete deployment of ESGF with containers re-engineering the initial work.  

The current status is that we have a complete ESGF Index and Data Nodes.  However, as a first cut, these are _without_ any access control implementation.
The latter is the subject of the next major effort which is move to a centralised system using an Identity Provider Proxy together with adoption of OpenID Connect.

As ever, the latest dev status is captured in the [Kanban](https://github.com/orgs/ESGF/projects/1)
