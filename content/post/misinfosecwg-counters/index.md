---
title: The MisinfosecWG Counters Workshop
subtitle: Moving From Admiration to Action
# summary: foo
authors:
- sj_terp
date: 2020-03-05
math: true
draft: false
diagram: true
tags: ["Disinformation", "Information Operations", "Cognitive Security"]
categories: []
image:
  placement: 3
  caption: 'Courses of Action wall — this visually anchored the workshop'
---

## The Misinfosec Working Group

{{< figure src="misinfosec1.png" title="MisinfosecWG timeline. We built infosec-based standards for describing and sharing information about disinformation incidents" lightbox="true" >}}

The Misinfosec Working Group (“misinfosecWG”) is part of the Credibility Coalition. It was formed around a standard for action: we wanted a way for the many groups and individuals that we saw starting to investigate disinformation incidents to quickly share information about them, in the same ways that information security groups share information through information exchanges like ISACs and ISAOs, and disclosure schemes like bug bounties. We also wanted, as the field of disinformation response grew, to build ways for groups and individuals to quickly look up and share information about the mitigations and other activities that worked (or might work) to counter active disinformation campaigns.

MisinfosecWG has come a long way since Pablo and I talked in 2018 about creating standards for misinfosec — the application of information security principles and practices to disinformation incident mitigation — and decided that CredCo was the only obvious place to incubate such a standards group. Walker and I started the CredCo misinfosec working group in December 2018, and since its official launch in January 2019, we’ve built a bridge between information security, misinformation and specialists in fields like narrative science (looking at you, John, Walker and Danielle), placed infosec-style response firmly inside disinformation response, and adapted existing infosec standards like ATT&CK and STIX into the AMITT standard for disinformation use, giving us the ability to transmit, share and analyze information about disinformation using existing information security technologies and techniques.

And in November 2019, MisinfosecWG ran the second of its workshops; the “Blue Team Workshop” on misinformation countermeasures. The last of these, the “Red Team Workshop”, in Atlanta, modeled the tactics and techniques used by disinformation creators, and produced the AMITT framework of disinformation tactics, techniques and procedures (TTPs). The DC workshop, held in the Atlantic Council’s meeting space, focused on how responders could mitigate and counter those TTPs.

## Why Run a Countermeasures Workshop?

{{< figure src="misinfosec2.png" title="A STIX diagram for a disinformation incident. The workshop was about creating more of the green box on the right (courses of action to counter incidents, techniques, tactics etc)" lightbox="true" >}}

MisinfosecWG has always had two main aims: to promote a more formal and rigorous classification of:

- Types of information-based attacks; and
- Types of defense from information-based attacks

We’d already covered the first bullet with our work on AMITT and STIX-based descriptions of disinformation TTPs. This workshop was all about our work on the second bullet: defense, and in particular, disinformation counters, mitigations and other potential responses.

Countering disinformation is a multi-disciplinary activity, so we enlisted experts on disinformation, cognitive security, information security, narrative and rumor tracking, diplomacy, trust and safety, counterterrorism and CVE from our target user communities: industry, academia, media, community, government and military. We stated the workshop goals up front:

- Draft a disinformation “Blue Team” playbook. Its intended users are defenders, information security people and organizations; its contents should be a set of responses to misinformation attacks, with information on networks, response types, frameworks, examples.
- Ideate supporting an operational global Cognitive Security response network. The audience for this is potential response centre participants and leaders, and its contents should be a set of processes, methods, understanding needed to connect actors, partners, collaborators and funders.

And we framed the first solution space by combining the stages that a disinformation incident goes through (its “tactics”) from AMITT with the types of action that could block or mitigate each of them (courses of action categories) to create an empty ‘grid’ on the wall.

Our aim in the workshop was to fill this grid with potential responses, then drill down into the details of some of those responses. First, level-setting. With all the different disciplines in the room, we used the AMITT framework and misinfosec pyramid (campaigns/ incidents/ narratives/ artefacts) to frame the work we were doing, including the idea that each object in the STIX graphs we create for each disinformation incident could potentially be paired with a course of action (the green icon, defined in information security as “an action taken to either prevent an attack or respond to an attack”) to mitigate, block or disable it, and that the ATT&CK idea of finding counters for each technique (the blue icons) was a good place to start.

## Existing Counters

We didn’t go empty-handed to the workshop. The MisinfosecWG team had already spent time looking for counters in our set of example incidents (in the AMITT GitHub repository), and looking at existing counter examples and types through a combination of existing knowledge and literature search (e.g. in the DoJ’s framework). Some well-known examples we gave of these are below, but we also encouraged attendees to think laterally about countering the techniques that they saw:

- US Cyber Command blocking internet services to the Internet Research Agency on the day of the 2018 US Midterm elections
- Twitter killing a pro-Saudi botnet spreading Khashoggi disinformation tweets
- Macron’s team creating data honeypots before French elections
- CISA’s “War on Pineapple” education sheets about disinformation

{{< figure src="misinfosec3.jpg" title="AMITT Tactics and Techniques — see https://github.com/misinfosecproject/amitt_framework" lightbox="true" >}}

We needed to frame these — to structure them so they weren’t a random collection of examples and suggestions. So we used AMITT’s TTPs (Tactics, Techniques, Procedures).

{{< figure src="misinfosec4.png" title="Courses of Action grid for AMITT tactics" lightbox="true" >}}

AMITT breaks disinformation incidents down into tactic stages. In infosec, when you map those tactics against the types of action that could be taken against each tactic stage, you get a Courses of Action matrix.

We used the JP 3–13 (2006 US military Joint Publication 3–13 on information operations) definitions for our action categories; there are many of these, but we used the subset of Detect, Deny, Disrupt, Degrade, Deceive and Destroy, adding “Deter” to the list.

- Detect: discover or discern the existence, presence, or fact of an intrusion into information systems.
- Deny: prevent the adversary from accessing and using critical information, systems, and services.
- Disrupt: break or interrupt the flow of information.
- Degrade: reduce the effectiveness or efficiency of adversary command and control or communications systems, and information collection efforts or means.
- Deceive: cause a person to believe what is not true. military deception seeks to mislead adversary decision makers by manipulating their perception of reality.
- Destroy: damage a system or entity so badly that it cannot perform any function or be restored to a usable condition without being entirely rebuilt.
- Deter: discourage

{{< figure src="misinfosec5.png" title="SANS scale for counters" lightbox="true" >}}

We also talked about counters in the context of the SANS scale from architectural through to offensive countermeasures.

## Brainstorming a Courses of Action wall

{{< figure src="misinfosec6.jpg" title="Courses of Action starting to fill up. Note the blank boxes in it, where we might need more work" lightbox="true" >}}

And then it was post-its time. We split into groups, and each group took a set of tactic columns to work on, and a large stack of blank post-its. They didn’t disappoint. The wall filled up (the wall rows were courses of action; the columns were AMITT tactic stages).

We had a wide range of ideas back from the groups. Because we forced people to think about countering the whole disinformation lifecycle, from strategic planning all the way through to after-action evaluations, we think we captured counters that haven’t been tried before, many of which are in the valuable “left-of-boom” area before a campaign reaches the general public.

{{< figure src="misinfosec7.jpg" title="Course of Action box for “Detect” on tactic “Develop Content”" lightbox="true" >}}

A post-it on a wall isn’t a response, so we asked teams to drill further into each set of counters — looking at who could take each action, how it might play out, what its side-effects might be. That produced a lot more detail, and yet more counters, all of which were added to a prototype technique-level playbook.

## Thinking about End Users

{{< figure src="misinfosec8.png" title="ISACs — just some of the bodies connected to the Cognitive Security ISAO" lightbox="true" >}}

Disinformation is a whole-system problem, and we took the opportunity to spend some time preparing for the next activity needed — coordinating whole-system response through bodies like the US ISAO system, and more specifically the prototype Cognitive Security ISAO, looking at what they do and how we as a group could support them.

## Making Counters Useful

{{< figure src="misinfosec9.png" title="Counters organised by metatag — see https://github.com/misinfosecproject/amitt_counters" lightbox="true" >}}

And then the workshop was done, but we’re not finished yet. We created a spreadsheet from the courses of action grid. After consolidating identical ideas, we have nearly 200 counters to analyze and make useful, plus suggested additions to AMITT etc.

MisinfosecWG has finished its incubation year with CredCo, and the team has created and is now working in a new community, [CogSec Collab](https://www.cogsec-collab.org/), that’s concentrating on supporting disinformation volunteer groups and individuals.

We’re still organising the counters. We have them tagged with tactic, techniques, groups who could be write up in our responses. We grouped by ‘metatags’: tags for similar activities, til we realised that that was a proxy for a top-down activity and started describing that instead. We have two reports in the works: one on how we found and organised counters, and another on the counters themselves. Roger and Eric are busy adapting ATT&CK technologies to carry the AMITT responses and playbook entries that we’re building. It’s going to take us a little while, but we’re still slowly moving forwards with misinfosec.




