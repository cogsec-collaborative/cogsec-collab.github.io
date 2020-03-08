---
title: The MisinfoSec Framework Takes Shape
subtitle: Misinformation, Stages, Techniques and Responses
# summary: foo
authors:
- sarajayne_terp
date: 2019-07-19
math: true
draft: false
diagram: true
tags: ["Disinformation", "Information Operations", "Cognitive Security", "Cyber Security"]
categories: []
image:
  placement: 3
  caption: 'Courses of Action wall — this visually anchored the workshop'
---

## Developing the AMITT (Adversarial Misinformation and Influence Tactics and Techniques) framework


On May 24, 2019, the CredCo MisinfoSec Working Group met for the day at the Carter Center in as part of CredConX Atlanta. The purpose of the day was to draft a working MisinfoSec framework that incorporates the stages and techniques of misinformation, and the responses to it. We came up with a name for our framework: AMITT (Adversarial Misinformation and Influence Tactics and Techniques) provides a framework for understanding and responding to organized misinformation attacks based on existing information security principles.

We’d like to provide a recap of what the working group came up with the day, as well as explain and discuss some of the key concepts we used to inform our work. It should be noted that the working group relied on [our previous work on the stages of misinformation](https://misinfocon.com/misinformation-has-stages-7e00bd917108), documented in a previous Misinfocon blog post.

## Who We Are and What We Do

Before we describe what we accomplished at the Carter Center in Atlanta on May 24, it’s a good idea to briefly explain who we are and the formal mission of the MisinfoSec Working Group:
The Credibility Coalition’s MisinfoSec Working Group (“MisinfoSec WG”) maps information security (infosec) principles onto misinformation. According to the The CredCo Misinfosec Working Group [charter](https://github.com/credcoalition/community-site/wiki/MisinfoSec-(The-Intersection-of-Misinformation-and-InfoSec)), our goal is to develop a tactics, techniques and procedures (TTP) based framework that gives misinformation researchers and responders a common language to discuss and disrupt misinformation incidents.

Our working group is also focused on contributing to the evolution of MisinfoSec as a discipline. This evolution is happening, as we’re seeing an emergence of presentations with slides referring to TTPs, and people starting to talk about building [ISAOs](https://www.isao.org/) (Information Sharing and Analysis Organizations) and [ISACs](https://en.wikipedia.org/wiki/Information_Sharing_and_Analysis_Center) (Information Sharing and Analysis Centers) — non-profit organizations that provide a coordinated central hub for gathering and sharing of cyber threat information for the US Government, specifically in relationship to misinformation.

## Establishing a Common Language for Communicating Threats

In order to coordinate misinformation response centers with each other, and share information easily, they’re going to need information-sharing standards for misinformation.
So, a key goal of our working group is to promote more formal, practical and rigorous treatment of types of information-based attacks, and types of defense from information-based attacks.
The working group’s deliverables will include a text resource consisting of definitions and a strawman framework combining the elements above, and an online article highlighting some common attacks in the wild.

So far, since January 2019, the group’s imperative has been to establish a common language for communicating about and responding to dynamic threats creating complex problems.
It’s equally important to help lead the effort to ensure that MisinfoSec (applying information security paradigms to misinformation campaigns) plays a key role in every conversation about cognitive security and information system resilience.

While we’re building upon [existing definitions of the (mis)information ecosystem](https://medium.com/1st-draft/information-disorder-part-1-the-essential-glossary-19953c544fe3), the Misinfo Working Group is also working at evolving the language and discipline. Acknowledging that [‘credibility’ can be definitely be recognized and identified](https://misinfocon.com/kermit-is-credible-and-this-is-good-for-news-f26f595a356e), and with an aim of providing more nuance to how coordinated misinformation is defined, [the following definitions](the following definitions) served as a foundation:

> **Disinformation**: False information that is deliberately created or disseminated with the express purpose to cause harm. Producers of disinformation typically have political, financial, psychological or social motivations.

> **Misinformation**: Information that is false, but not necessarily intended to cause harm. For example, individuals who don’t know a piece of information is false may spread it on social media in an attempt to be helpful.

> **Malinformation**: Genuine information that is shared to cause harm.This includes private or revealing information that is spread to harm a person or reputation.

With these concepts and assumptions in mind, our working group operates according the definition of misinformation attack that we defined in [Misinfosec: Applying Information Security Paradigms to Misinformation Campaigns](https://dl.acm.org/citation.cfm?id=3316742&dl=ACM&coll=DL) (2019) by Christopher R. Walker, Sara-Jayne Terp and Pablo C. Breuer:

>*We use ‘misinformation attack’ (and ‘misinformation campaign’) to refer to the deliberate promotion of false, misleading or mis-attributed information […] We are especially interested in misinformation designed to change beliefs in a large number of people.*
>
>*Actors behind misinfo attacks include nation-states, institutional actors, grassroots trolls and financially-motivated freelancers. Common motives include geopolitical aims, issue-promotion or financial gain.*

## Our Task in Atlanta: Building a MisinfoSec Framework

So, on May, 25, the MisinfoSec Working Group assembled at CredConX in Atlanta to build a framework. The meeting room at the Carter Center was like our lab for the day. And, while our efforts were not in the league of [Banting and Best](https://www.sciencehistory.org/historical-profile/frederick-banting-charles-best-james-collip-and-john-macleod) whose discovery of insulin improved the lives of millions of people with diabetes, we found a striking parallel.

To use a metaphor, the problems plaguing today’s information ecosystem is like diabetes.

As [Rand Waltzman](https://www.linkedin.com/in/randwaltzman/) and [Renee DiResta](https://twitter.com/noUpside) have noted, “Disinformation is a not a problem that can be solved. It’s like a chronic disease that can be managed — not cured- allowing the afflicted to lead a moderately normal life.”

As we worked together at the Carter Center, on May 24, we were able to build upon the following our team’s existing work:

- A strawman framework we created for the [Web Conference MisInfoWorkshop2019 talk](https://www2019.thewebconf.org/) — not detailed, with a set of stages that were designed to be argued about. The paper is “Applying Information Security Paradigms to Misinformation Campaigns.” See [our colleague Christopher Walker’s presentation here starting at the 1:00:00 mark](https://www.youtube.com/watch?v=nzQWbTOdAAE&t=3735s).

- A mapping of marketing, psyops and new misinformation stage models against the cyber killchain.

- The [misinformation pyramid](https://misinfocon.com/misinformation-has-stages-7e00bd917108), so we could talk about the different viewpoints of attackers (red team) and defenders (blue team)

- [Boucher’s list of techniques](https://medium.com/@timboucher/adversarial-social-media-tactics-e8e9857fede4), mapped onto [Ben Nimmo’s “5 D’s” strategies](https://twitter.com/benimmo/status/670230827377295360?lang=en-gb)

- An example of each of the stage-based frameworks we’d compared earlier in the day

- A list of the existing ISACs (Information Sharing and Analysis Centers), so we remembered who we’re trying to support


{{< figure src="misinfosec1.jpeg" lightbox="true" >}}

Our meeting goal at the Carter Center in Atlanta was to build a framework of misinformation, stages, techniques and responses. In particular, the Working Group gathered to further solidify our work (since March 2019) on developing framework stages and technique templates for incident responders by:

- Increasing our set of techniques

- Mapping techniques to stages

- Solidifying stage labels

- Documenting potential technique responses

To do this, in Atlanta the Working Group came equipped with these common terms of reference:

> **A technique**: Deployed by [Advanced Persistent Manipulators](https://securingdemocracy.gmfus.org/advanced-persistent-manipulators-part-one-the-threat-to-the-social-media-industry/), can include relatively benign approaches, such as the use of humour and rhetoric, all the way through to the forging of documents or the use of false identities.

> **A stage-based model**: Similar to the Cyber Kill Chain. We’ve previously outlined our premise about [misinformation as a process of stages](https://misinfocon.com/misinformation-has-stages-7e00bd917108).

> **A response**: There is no definitive collection of best-practices or playbook of successful counteractions. The MisinfoSec Working Group has defined a response as one step of a strategic process, a holistic one that starts with assessing a technique in the context of seeing it as part of a chain-of-events. With an evolving playbook we agree with [Clint Watts’](https://twitter.com/selectedwisdom) current position that “the goal is to take an approach that will anticipate changes in threat behavior and proactively disrupt nefarious activity rather than reactively respond to it.”

## The First Task: Grouping Techniques for Spreading Misinformation

Before the session, we prepared by listing the techniques used in each of our list of incidents, then created a post-it for each technique. Each technique post-it held an incident number and description, with techniques from incidents attributed to Russia documented on blue post-its, yellow post-its for non-Russia attribution.
For the next step, we gathered all of the post-its, and then invited meeting attendees to cluster them into stages (pink post-it notes), and order the stages on a wall from left (campaign/incident planning) to right (campaign/incident completion).
Mapping the wall was a process of grouping identical techniques into stacks, and talking through the stages, discussing what belonged where in the order.

{{< figure src="misinfosec2.jpeg" lightbox="true" >}}

Satisfied with this first exercise, we revisited [our collection of existing models](https://misinfocon.com/misinformation-has-stages-7e00bd917108) (ATT&CK model, marketing funnels, psyops, Department of Justice model), and models from Renée diResta, Ben Decker, Clint Watts and Bruce Schneier. We investigated whether their respective stages and techniques were represented in our model on the wall, and if not, added them. Surprises included that the [stages in the New York Times model](https://www.lawfareblog.com/toward-information-operations-kill-chain) (used by Bruce Schneier) were actually techniques (more on this in a subsequent blog post).
Having established a model, we needed to test it. We spent just over an hour adopting a “red team” (attacker) mindset in order to build an imaginary misinformation campaign. It was invaluable walking through each stage (see Sara-Jayne Terp’s [Misinformation has stages](https://misinfocon.com/misinformation-has-stages-7e00bd917108) blog post for more details) to see whether we’d missed anything.

{{< figure src="misinfosec3.jpeg" lightbox="true" >}}

No surprise, we had missed a few details, and so took the opportunity to add both stages and new techniques as we walked through the exercise.

## The Next Task: Developing Techniques to Combat Misinformation

With a tested model, after we transferred all of the information into a new spreadsheet, we were ready to dive into individual techniques. As part of this next stage of our work, we looked at techniques both individually and as part of a process, and we spent time thinking about how we could counter or disrupt them.

Given our time constraints, we focused on techniques that had amassed the most post-its during our previous exercise. More post-its meant the techniques were typically used in multiple incidents, such as fake Facebook group and Twitter bots and trolls.

At this stage, some additional discussions, which lead to useful pointers, included:

> **Think in terms of feedback loops, rather than linear processes**: While we might have a linear stage model, what we’re really observing are cycles and feedback loops (which is already built into ATT&CK Adversarial Tactics, Techniques, and Common Knowledge).

> **Look for both content and context**: The network-building stage is about creating the context of a campaign; the content creation stage is about creating the content for it. These concepts both map nicely to our blue team idea of looking for both content and context.

> **Ask who is leading a misinformation campaign**: We looked at how adversaries use metrics and measurement, and plan or deploy countermeasures. Is it implicit that there’s a “general manager” watching over the campaign, checking metrics and so on?

> **Understand different levels of defence**: The working group looked at technique-level defence vs procedure-level defences (e.g. disrupting the chain of work), and doing that as far left in the stage diagram as possible. For example, we looked at how online or digital network building looks like a good location to disrupt, or getting inside the organisational places for doing both recon and delivering counters.

{{< figure src="misinfosec4.jpeg" lightbox="true" >}}

## Don’t Forget the Boom!

And, during the day at the Carter Center, we didn’t forget the “boom,” a term borrowed from the military meaning the moment before [a bomb](https://www.urbandictionary.com/define.php?term=a%20bomb) explodes (as opposed to “right-of-boom”, which comes after). In particular we’re very interested in working towards the disruption, denial and displacement of the left-of-boom techniques.

# What’s Next for CredCo’s MisinfoSec WG

By the end of our working session at CredConX at the Carter Center in Atlanta on May 24, we successfully created AMITT (Adversarial Misinformation and Influence Tactics and Techniques), a preliminary MisinfoSec framework that included stages, techniques and responses. Next, the working group needs to test it with different demographics, continue the counter-discussions and support the new ISAOs as they come online. As well, stay tuned for our June report — our goal is to have Version 1.0 online by the end of July.

*Participants at the May 24 session in Atlanta included Sara-Jayne Terp, Christopher Walker, John Gray, Courtney Crooks, Chau Tong and Renee DiResta. Working group member Pablo Breuer was absent for the day. Many thanks to them and to our guests — Amy Bruckman, Benn Konsynski, Richard Foard, David Carroll, Michael Best, Nitin Agarwal and Tanushree Mitra — for their thoughts and input.*
