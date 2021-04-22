---
title: Cogsec Collab MISP Community
# summary: foo
authors:
- VVX7
date: 2020-03-26
math: true
draft: false
diagram: true
tags: ["Disinformation", "Information Operations", "Cognitive Security", "MISP", "Threat Intelligence"]
categories: []
image:
  placement: 3
  caption: ''
---

## A community dedicated to information operations

We're proud to announce the CogSec Collab MISP Community - the first public MISP sharing group dedicated to misinformation and information campaigns.

Our community seeks to connect misinformation researchers and responders  by providing tools to streamline investigation and reporting on  disinformation and information campaigns.  By making our MISP instance available to the community we're enabling researchers to generate and share information operations data in MISP JSON or STIX format at just a click of a drop-down menu.

We look forward to working with our partners to provide access to disinformation documentation and sharing standards, indicators, countermeasures and playbooks. 

Send us an email to request access.


## MISP

The MISP Project started out as a way to share malware indicators.  It's grown to include much more - financial fraud, climate data and most recently COVID-19 cases.

{{< tweet 1239864641993551873 >}}

At its core MISP is an automated correlation engine.  It assists analysts in finding interesting relationships between indicators and contextualising the data. For Cogsec Collab, it's a means to provide structured threat intelligence to cross-sector partners with highly diverse requirements.



## AM!TT Misinformation Pattern Galaxy

{{< figure src="galaxy_list.png" title="Descriptions of AMITT Techniques in the MISP Misinformation Pattern Galaxy." >}}

Our first achievement  was the integration of the [AM!TT Framework](https://github.com/cogsec-collaborative/AMITT) as a [MISP Galaxy](https://www.misp-project.org/galaxy.html#_misinformation_pattern).  It contains the tags and definitions needed for describing the misinformation tactics and techniques present in a specific information operation.


## AM!TT Navigatord

{{< figure src="amitt.png" title="The MISP Project kindly developed this built-in technique navigator." lightbox="true" >}}

Applying the AM!TT galaxy information to an event must be easy in order to encourage use by already overburdened information researchers.  The MISP Project developers kindly created an inline AM!TT Navigator to respond to this need for conveniently tagging events with AM!TT techniques. 

With this tool, analysts can simply click on the relevant techniques found in a report or sighting to include that information in the misinformation event data.


## DFRLab Dichotomies of Disinformation

{{< figure src="dfrlab.png" title="Atlantic Council's DFRLab Dichotomies of Disinformation" lightbox="true" >}}

Also included in the CogSec Collab MISP is [Atlantic Council's DFRLab](https://www.atlanticcouncil.org/programs/digital-forensic-research-lab/) [Dichotomies of Disinformation](https://github.com/DFRLab/Dichotomies-of-Disinformation) which is a new standard for describing information campaigns that can be used alone or in complement to the AM!TT framework.

The work of the DFRLab is included in MISP as a Taxonomy - a set of machine tags for describing indicators and events. 



## Future Work

From this point our next steps are to  build elf communities and equip them with the tooling and  training needed to be effective.

MISP will play an important role in distributing misinformation threat data but it's just a tool; it's the people who make the community of users that can make it great.  If you work in the disinformation space, please reach out.  Come talk to us.

As things develop we'll have more to say about our disinformation sharing community.  For now we'd like to thank the [MISP Project](https://twitter.com/MISPProject) developers for their excellent work and commitment to FOSS threat intelligence tooling.

Thank you!




