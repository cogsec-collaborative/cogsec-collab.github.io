---
title: Distributed Defence Against Disinformation
summary: 2020 is where cognitive security, the idea of treating disinformation as an infosec problem akin to malware, really caught on.
authors:
- sj_terp
date: 2020-09-13
math: true
draft: false
diagram: true
tags: ["Disinformation", "Information Operations", "Cognitive Security", "Information Security"]
categories: []
image:
  placement: 0
  caption: 'Face Mask Exemption Override Card'
---

I spoke recently at Disclosure — a conference started by Marc Rogers, bringing together interesting systems thinkers across information security. Last year, I spoke about how to adapt infosec to disinformation defense; this year about what the CogSecCollab leads have learnt from running the CTI League’s Disinformation response team.


2020 is where cognitive security, the idea of treating disinformation as an infosec problem akin to malware, really caught on. First, let’s talk about definitions. Misinformation is false content. In disinformation, the content doesn’t have to be false — some of the best disinformation campaigns use mostly-true information twisted out of context, mis-attributed, inorganically amplified etc etc. What interests our teams are attempts at large-scale belief change or emotion change, that mislead people about the content or context of information.

# 2020: Not your Grandma’s Disinformation Ecosystem



The League concentrates on Covid19-related disinformation. It’s useful to talk here about narratives, because there are far less narratives than messages, making them easier (especially with text-based machine learning techniques) to track. The League team keeps a list of hundreds of Covid19 narratives, bucketed into top-level categories from origin myths (‘escaped bioweapon’), covid isn’t serious, medical scams (covid cures including MMS and alcohol), resolution (‘country X has a cure already’), to crossover narratives. In 2020, we saw a lot of Covid19 crossover narratives, where existing groups like antivaxxers and hardcore rightwingers met and joined forces, and conspiracy theories were recycled and combined into new narratives. We loosely grouped crossover narratives into conspiracies (5G, antivax, depopulation, black helicopters), freedom rights (anti-stayathome, second amendment, immigration, etc), and geopolitics (covert and overt from China, Iran etc, “blue check” accounts), and expect this type of recycling to become normal.

If you want to understand disinformation, you need to understand the motivations. Geopolitics (follow the countries), power gain (follow the divisions), financial gain (follow the money), attention seeking (follow the sharks, satire and other LOLs), and online discussion (follow the opinions, conspiracies, protest, nazis etc). In 2020, despite all the news about geopolitical disinformation, a lot of the disinformation we tracked was financially-motivated. In a lot of the incidents we tracked, we found people trying to make money — either originating, or attaching themselves to incidents. Etsy and Amazon shops selling t-shirts, more sophisticated sales operations selling “cures”, networks of websites selling advertising space. There are crossovers here too: we tracked one Covid19-related incident back to someone selling their book about 5G.

Money usually needs URLs. If you’re making money online, at some point you’re going to need a URL: the Etsy or Amazon shop, or your own domains that you can control sales through, sell advertising space on, collect user details to sell etc. An example of this is The NaturalNews network — interesting because it started as a healthcare misinformation site, then broadened out — for example, we found it amplifying the antifa on buses story this year; and useful because they track the zeitgeist of current disinformation. If you’re tracking disinformation, URLs become important because they help you find more of it: a URL is an entry point into a network, from which we can map out a network of domains, associated social media, linked disinformation campaigns etc. We’ve done well with tools like domaintools, backlink checkers, and Builtwith, finding related sites through registrations, google analytics, and advertising tags.

Disinformation evolved in 2020. Some examples:

- We tracked WeWontStayHome because it was part of the wider Covid19 health incident. It was a small incident, but it seeded a much larger incident, OperationGridlock, later. We also saw this incident spread across countries and states. This was an early use of astroturfing: creating and populating a group for each state.

- When we created the AMITT framework for tracking disinformation techniques, we included “going physical” as a category because even though it was rare then, we thought it might become important. In 2020, a lot has gone physical, including “face mask exemption cards” — laminated cards intended to exempt their bearers from covid19 mask requirements in stores etc. We’ve seen a lot of homespun ideas, in this case a card with a long spiel, HIPAA misspelt etc, being picked up and productionized either for money, to support other campaigns or both (e.g. the main site that productized mask exemption cards takes PayPal donations, and collects user details). We’ve also seen this cross countries and communities, e.g. a more professional-looking mask exemption card in Canada, listing organizations targeting parents.

- 2020 isn’t all bad: it’s a breakout year for countermeasures too, from the kPop fans flooding extremist hashtags with boy band images, to social media companies starting to take down content that isn’t just immediate threats to life. It’s also been a good year for homegrown countermeasures, like mask exemption override cards: laminated cards that ‘cancel’, game-style, mask exemption cards.

- Disinformation doesn’t exist in a vacuum: it’s part of an information space. If you just remove the disinformation, you leave vacuums, voids in the places where people search for information. People will still search: if you remove the wrong information, you need to have information or routes to information in ways that they can consume it, in the places that they want to consume it. Many good information teams emerged in 2020 — the League team has partnered with one of them, the RealityTeam, working out how they can rapidly deploy counter-narratives and information, in response to new incident narratives.

- Some developing-world spam and marketing companies are pivoting to provide disinformation as a service — RecordedFuture did a good report on this, and the use of a fake NGO in Ghana to target African Americans was interesting. Disinformation is starting to get the attention of organized crime (there’s a UNODC report out on this soon), but the economics aren’t there yet: at the moment, ransomware is a better business model for large amounts of money, and businesses and principals are mostly caught up in disinformation campaigns rather than targets of it. Deepfake tech is still too complicated and expensive to massively scale, but it’s coming. We already have text, and the next evolution is to more video and voice. The likely business transition is from small specialized agencies, e.g. a boutique capability, then market expansion where disinformation becomes a commodity capability.


That’s where we are in 2020, but CogSecCollab always looks ahead. We do this from a combination of responding to disinformation as a Blue Team (running a response plan, building playbooks, tracking campaigns, incidents, narratives and artifacts), and learning from examples by running weekly Red team exercises. Topics we’ve covered in those exercises include running a “disinformation as a service”/alternative marketing company, running a hostile social media platform, mixing disinformation with coordinated sensor spoofs, and extending an existing narrative (e.g. anti-medical safety). We learn a lot from these. Sometimes they give us a heads-up on likely next steps in disinformation campaigns (e.g. potential disinformation narratives as children went back to school); other times we gain insights into how and why disinformation creators operate the ways that they do.

# 2020: Cognitive Security is real now. Join us

Cognitive security is a rapidly growing domain that interacts with cyber and physical security, and includes things like information operations and disinformation. We look at this from a set of overlapping axes.

Collaboration. “This isn’t a silver bullet problem, it’s a thousand-bullet problem” — Pablo Breuer. Disinformation is a distributed, heterogeneous problem. It needs a similar response, one that’s collaborative, heterogeneous and connected. Lots of different groups at lots of different scales, that have to work together, and we need to connect them, in a way that respects the groups, the subjects of disinformation, and the accounts and groups being investigated. Practically, that means privacy, sharing, and standards.

{{< figure src="pyramid.png" title="Misinformation Pyramid" lightbox="true" >}}

Layers. We’ve written about this model before: Longer-term campaigns (antivax, destabilize national politics etc), containing shorter-term incidents (e.g. a burst of activity around a specific topic or event), based on narratives, (the stories we tell ourselves about who we are, who we belong to, who we don’t belong to, what’s happening in the world), which show up as artifacts: messages, images, accounts, groups, relationships.


Threat intelligence Tasks. We’re doing threat intelligence — we want to find, predict and neutralize current and future threats.That rests on intelligence skills — assessing the situation picture using the five Ws (who, what, when, where, why, and how): what’s happening, with best guesses about origins and future moves; who’s involved (including attribution), why (intent), and how (tactics and techniques). For disinformation, this is usually OSINT (open source intelligence) — finding that situation picture using publicly-available data, supported by data science — finding patterns in big data that’s arriving fast across many channels (as Marc Rogers noted last year, the 3V volume, velocity, variety model is what makes modern disinformation tracking different). Attribution — working out who’s responsible for a disinformation incident — is hard. You don’t have full access to data, and there are incentives for people to obfuscate and hide who they are. At best, attribution is probabilistic, but even a hint can help us assess potential moves, and countermoves.

{{< figure src="analytics_maturity_model.png" title="Data Science Ladder (from https://www.ecapitaladvisors.com/blog/analytics-maturity/)" lightbox="true" >}}

Analytic maturity. The data science ladder also applies to disinformation response: work ranges from assessing what’s happened (e.g. traditional statistical analysis), to predicting what might happen next (machine learning), to moves and countermoves in an interactive environment (applied game theory). Disinformation response has been moving up this ladder, and is currently around the prescriptive analytics point on it.

Response timescales. There are different team response timescales: strategic (weeks/months/years), issue-focussed work, e.g. long-form journalism exemplified by Stanford Internet Observatory, U Washington, Shorenstein Center, Bellingcat, DFRlab, Grafika and social media platforms; operational (days/weeks), project-focussed work that’s usually embedded with development teams working in AI/ML-based disinformation data and tool companies; tactical (hours/days), incident-focussed work, responding to disinformation as it happens, exemplified by the New York Times, CTI League, some of MLsec, and the crisismapping teams that cover disinformation. Each of these work differently. If you have hours, all you care about is stopping the flood of disinformation; if you have months, you can get into attribution, geopolitics and motives. In 2020, many of the strategic groups started responding faster and became more tactical.

# Disinformation Incident Response

This isn’t a new problem: I’ve addressed it before. As a crisismapper, I set up procedures for data analysis and sharing in reaction to sudden-onset disaster events, set up and connected groups doing this around the world. These activities map to disinformation too.

We’re tracking Covid19 incidents through the **CTI League** disinformation team. The League is the first Global Volunteer emergency response Community that defends and neutralizes cybersecurity threats and vulnerabilities to the life-saving sectors, related to the current COVID-19 pandemic. The disinformation equivalents of the League’s main work are:

- **Neutralize**: Disinformation incident response: triage, takedown, escalation.

- **Clearinghouse**: Collate and share incident data, including with organizations focusing on response and counter-campaigns.

- **Prevent**: Collate disinformation indicators of compromise (IoCs) and vulnerabilities; supply to organizations.

- **Support**: Assess the possibility of direct attack, and ways to be ready.

The rest of this post is about the incident response part of that. To do this, we need the usual process triangle of people, process, technology and culture:

- Enough trained people (understand disinformation, understand threat response) to be able to respond fast enough and make a difference to an incident (that includes noticing incidents in time to respond)
- Enough ways to make a difference (including outbound connections)
- Safety culture including mental health and OPSEC
- Fast, lightweight response processes
- Technology —to support and speed up analysis, storage etc
- Sharing technology — to get data to responders in ways they understand

CogSecCollab has been working on processes, tools, and training to support this. We started with the disinformation adaptations we made to threat intelligence tools (HIVE and D3PO for case tracking, MISP for intelligence sharing, and data tools for analysis support): the MISP work in particular is already shared with team in NATO, the EU and other countries. We’ve also been cleaning up the CTI League disinformation process manual, and are starting to share that with other groups for comment/ improvement; after that, we plan to share our team training courses (e.g. Data Science for Disinformation Response — a repurposed university course).

{{< figure src="ooda.png" title="John Boyd’s OODA (Observe, Orient, Decide, Act) Loop" lightbox="true" >}}

Almost four years ago, I started talking about the overlaps between disinformation, information security, machine learning, and military competition short of armed conflict, and used Boyd’s OODA diagram then. For Boyd, it was about understanding why some pilots were better at winning dogfights, couched in terms of interacting decision loops. In 2020, that’s still a useful way to think about the pieces we need in a response.

# Observe: 2020’s Decade of Tracking Covid19 Disinformation

CTI gets feeds in from other groups, from its own monitoring and from its own members. Most alerts start with an artifact: an image, a URL, a piece of text. First, we have to decide whether to treat this as an incident. The three big questions we ask are about the potential harm from this incident, whether it’s disinformation, and whether we’re the best team to respond to it. For harm, we look at harms frameworks, and think about what the potential effects of an incident are, its size, coordination and targets. On disinformation, we ask where the falsehood is (e.g. is this misinformation or disinformation, are these fake groups, profiles, amplification etc), and whether it’s a different type of falsehood, e.g. phishing. On whether we’re the best team to respond, we ask if it’s in our area (e.g. covid19), whether other teams are already tracking and responding, if we have the resources to respond (this is long-haul work: burning out teams is bad), and do we have a reasonable chance of doing something useful about the incident. When assessing, we also look at the information we already have. For instance, we see a lot of repeat offenders, so we look for things like known medical scams. No team works alone, so even if an incident isn’t responded to, best efforts should be made to get alerts out, if needed.

Once we start an incident, our first job is to gather enough information to determine whether we should act, hand this information over to another party, stand down, or not act but keep a watch on this area. This is usually a mixture of artifact-based activity analysis, network analysis and fact-checking:

- Activity analysis: Tracking artifacts (messages, images, urls, accounts, groups etc), e.g. finding artifact origins, tracking how an artifact moves across channels/groups etc, and finding related artifacts. Detecting AMITT Techniques, e.g. detecting computational amplification; detecting, tracking and analyzing narratives.
- Network detection: Finding inauthentic website networks (pinkslime). Finding inauthentic account and group networks (including botnets).
- Credibility/ Verification: Fact-checking: verifying an article, image, video etc doesn’t contain disinformation. Source-checking: verifying a source (publisher, domain etc) doesn’t distribute disinformation.

(This is the incident-based tactical work. We also need monitoring work — spreader analysis — looking for infrastructure and accounts that are set up in advance of incidents, including sock puppet accounts “laundered” and left to mature).

Volume, Velocity, Variety: we can’t do that quickly enough with humans alone. We have to speed that up with machines, and here are some of the places that can be done.

- Graph analysis: finding super-spreaders, finding rumor origins, uncovering new artifacts, tracking movement over time
- Text Analysis: finding themes, classifying text to narratives, clustering text to narratives, searching for similar text/narratives
- Image, video, audio analysis: clustering images, searching for similar images, detecting shallowfakes.

CogSecCollab / CTI League Disinfo have already been using graph and text analysis, and experimenting with ways to cluster images so we can minimise the number of times we expose humans to sometimes-difficult images. This matters because exposure is cumulative, and if we can avoid exposing someone to 100 near-identical difficult images or texts, that’s useful.

# Orient: Getting the Situation Picture

Here we come to sensemaking, or understanding what you observed, in context. This includes looking at what we’ve collected, to work out what’s happening and might happen across the whole incident. One way the League team does that is by analyzing the connections between incident objects, using MISP. MISP is an open source threat intelligence platform that we’ve repurposed from malware to disinformation (CogSecCollab runs the MISP disinformation community). MISP is built on STIX, the sharing standard used by ISACs and ISAOs. We extended this slightly for disinformation, adding object types for incidents and narratives, and using AMITT for the attack patterns (see [https://github.com/cogsec-collaborative/amitt_cti](https://github.com/cogsec-collaborative/amitt_cti)).

{{< figure src="plandemic.png" title="AMITT TTP Framework, Plandemic example" lightbox="true" >}}

We’ve talked about the AMITT Framework before. It’s how we break an incident into techniques that we can analyze and counter. AMITT is now embedded in MISP, and we’ve handed it over to MITRE to manage. We tick the AMITT boxes during observation. During Orient, we look at this diagram to work out what’s happening, how we might respond, and if we catch an incident early, which downstream techniques might be used in that incident too. (The example here is Plandemic — a debunked conspiracy theory video which makes some false claims about the nature of COVID-19. We mapped it in AMITT to help us understand what capabilities the actor has and potentially how they’re resourced.)

What we get out of Orient is an incident report, containing a summary, narratives, techniques, artifacts and objects. We also get a MISP event that we can share with other groups either directly or by email, via their threat intelligence tools etc. We added a few other things to MISP for this: Object types for common social media platforms, and code to load these into MISP using single-line commands in Slack, because speed is everything in a tactical response; new relationship types, to make the graphs that users can traverse in MISP richer; and taxonomies (DFRLab’s Dichotomies of Disinformation, and a NATO-led tactical variant) to cover things like types of threat actor.

# Decide/Act: Options on Countermeasures, Mitigations, Resilience, Collaboration, Interaction

After Orient, we Decide. In 2020, we stopped “admiring the problem”. Questions we now need to ask at the end of analysis include: What are our options? Should we act? Do we want to? What are the ways that we, and the people connected to us, could affect a disinformation incident?

First, the who. Potential responders include the whole of society, including the infosec bodies already linked by the ISAOs and cyber Interpols. That’s platforms, law enforcement, government, elves (volunteer groups), the public, online and offline influencers, media, nonprofits, educators and corporations.

{{< figure src="countermeasures.png" title="One countermeasures view from https://github.com/cogsec-collaborative/amitt_counters" lightbox="true" >}}

And the what. In 2019, MisinfoSec worked on mitigations and countermeasures, building a course of action matrix from the AMITT tactic stages and a variant of the JP-3 list of effects: detect (find them), deny (stop them getting in), disrupt (interrupt them), degrade (slow them down), deceive (divert them), destroy (damage them), and deter (discourage them), or the TL;DR version: prevent access, break flow, add friction, honeypot, damage, and remove the incentives to create disinformation in the first place.

CogSecCollab has built theory and examples for effects-based, tactic-based and doctrine-based countermeasures. The CTI League team is using effects-based counters: reporting to law enforcement, platforms, and registrars, with CogSecCollab helping to connect the RealityTeam counter-narratives group back to the CTI League.

Having looked at options during Decide, it’s time to Act: make a change in the environment, and potentially start interacting with it. When you act in a disinformation space, you’re acting in an environment, with a lot of other humans and machines in. And what you can end up in is a multiplayer game, where you’re each acting in response to each other, and playing off against each others’ resources. Grugq, Pablo and myself have been working on this. But that’s for another discussion.

That was a quick spin around CTI League disinfo and CogSecCollab in 2020. You can learn more about the teams at [https://cti-league.com/](https://cti-league.com/) and [https://cogsec-collab.org/](https://cogsec-collab.org/).









