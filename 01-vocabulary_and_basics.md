---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Vocabulary and basics"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Vocabulary and basics in threat intelligence course"
keywords:
  - "threat"
  - "intelligence"
  - "intel"
  - "ti"
  - "course"
  - "vocabulary"
  - "basics"
color: "#ffffff"
class:
  - "invert"
style: |
  section.center {
    text-align: center;
  }
  table strong {
    color: #d63030;
  }
  table em {
    color: #2ce172;
  }

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
# Vocabulary and basics

![bg right:30%](images/01-arrow_keys.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
Lots of different terms and abbreviations are thrown around.  

(Sometimes used interchangeably :-/ )  

**Let's try to define some of them!**

![bg right:30%](images/01-arrow_keys.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Edenpictures (CC BY 2.0)" -->
## Threat
Bad stuff that we don't want to happen.  

Unwanted events with negative consequences.  
  
Earthquakes, terrorism, lawsuits, ransomware... 

![bg right:30%](images/01-abstract_building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Edenpictures (CC BY 2.0)" -->
## Threat actor
Group or individual that _wanna do bad stuff_
towards other groups or individuals.  

Intelligence agencies, criminal gangs,
hacktivists, disgruntled employees...

![bg right:30%](images/01-abstract_building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
## Asset
Thing belonging to a target that a threat actor
may try to abuse to achieve their goal(s).

Servers, network equipment, endpoint devices
and software running on these computers.  

Some include confidential information and
personnel (_OBJECTIFICATION!_) in their definition.  
  
(Let's keep our focus on IT assets)

![bg right:30%](images/01-cyberpunk_wall.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Asparukh Akanayev (CC BY 2.0)" -->
## Vulnerability
Weakness that can be abused to affect
the security of an asset.  

Software bug, default/bad password,
enabled debug functionality...  

![bg right:30%](images/01-brick_hole.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% The Preiser Project (CC BY 2.0)" -->
## Exploit
Tool or method used to abuse a vulnerability.

## Attack
Attempt to use an exploit against an asset.

![bg right:30%](images/01-pcb_man.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
## Attack surface
Assets exposed towards potential
threat actors that may be attacked.  

The attack surface may not look
the same to all threat actors.

![bg right:30%](images/01-radar.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
Services exposed towards the Internet.

Systems accessible by customers/partners
over a dedicated VPN tunnel.

Hosts exposed on internal office network.

Physical interfaces on industrial equipment.

APIs and other functionality accessible to
a (compromised) application/container. 

![bg right:30%](images/01-radar.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yana Sychikova (CC BY 4.0)" -->
Let's try putting these
terms to use, shall we?

![bg right:30%](images/01-nanoart_crystallites_lightning.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yana Sychikova (CC BY 4.0)" -->
A **threat actor** known as _Grumpy Bear_
enumerated the **attack surface** of
our Internet exposed systems.
  
They identified a **vulnerability** in
one of our **assets**: the VPN server
provided by _UltraEnterPriseSec Inc_.
  
They utilized a publicly available
**exploit** from [_Metasploit_](https://www.metasploit.com/) in their
**attack**, based on information
provided by the system logs.

![bg right:30%](images/01-nanoart_crystallites_lightning.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Gobi (CC BY 2.0)" -->
## TTPs
Describes (known historic) behavior
of a threat actor.  

**T**actics _(high-level)_,
**T**echniques _(mid-level)_ and
**P**rocedures _(low-level)_.  

Used together with target analysis
(basically "who was targeted") and other
indicators for **threat actor attribution**.

![bg right:30%](images/01-cyborg.jpg)

<!--
https://www.splunk.com/en_us/blog/learn/ttp-tactics-techniques-procedures.html
https://www.proofpoint.com/us/threat-reference/tactics-techniques-procedures-ttps
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Gobi (CC BY 2.0)" -->
**Tactic**: Steal sensitive information
and use it as blackmail for extortion.

**Technique**: Gain access to victim's email account
through "credential phishing" (social engineering).

**Procedure**:
Utilize the freely available tool ["Gophish"](https://getgophish.com/) to
send phishing emails claiming that the user must
change their password, setup redirect through
Google Docs domain to trick spam filters...

![bg right:30%](images/01-cyborg.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Fibreman (CC0 1.0)" -->
## The CIA triad
Helps us break down what "secure" means.

**C**onfidentiality,
**I**ntegrity and
**A**vailability.  

"Thought-tool" that can be used to discuss
priorities, expected outcome of changes...

(More about how to use it later...)

![bg right:30%](images/01-laser.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kārlis Dambrāns (CC BY 2.0)" -->
## Quantifying risk

![bg right:30%](images/01-door.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kārlis Dambrāns (CC BY 2.0)" -->
**Risk \~=**
**Consequences of bad thing \* Probability**.  

Tsunami washing away Stockholm data center \*
Probability of event \~= Extremely low risk.  

Secrets being stolen from outdated system _Z_ \*
Probability of event \~= Low-to-medium risk.  

![bg right:30%](images/01-door.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
## Wrapping up

![bg right:30%](images/01-arrow_keys.jpg)
