---
SPDX-FileCopyrightText: © 2023 Menacit AB <foss@menacit.se>
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
  
Earthquakes, terrorist attacks, lawsuits, ransomware... 

![bg right:30%](images/01-abstract_building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Edenpictures (CC BY 2.0)" -->
## Threat actor
Group or individual that _wanna do bad stuff_ towards other groups or individuals.  

Intelligence agencies, criminal gangs, hacktivists...

![bg right:30%](images/01-abstract_building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
## Asset
Thing belonging to a target that a threat actor may try to abuse to achieve their goal(s).

Servers, network equipment, endpoint devices and software running on these computers.  

Some include confidential information and personell (_OBJECTIFICATION!_) in their definition.

![bg right:30%](images/01-cyberpunk_wall.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Asparukh Akanayev (CC BY 2.0)" -->
## Vulnerability
Weakness that can be abused to affect the security of an asset.  

Software bug, default/bad password, enabled debug functionality...  

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
Assets exposed towards threat actors that may be attacked.  

The attack surface may not look the same to all threat actors.

![bg right:30%](images/01-radar.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Gobi (CC BY 2.0)" -->
## TTPs
**T**actics,
**T**echniques and
**P**rocedures.  

Describes behavior of a threat actor.  

Used together with target analysis and other indicators for attribution.

![bg right:30%](images/01-cyborg.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Fibreman (CC0 1.0)" -->
## The CIA triad
**C**onfidentiality,
**I**ntegrity and
**A**vailability.  

Thought tool that can be used to discuss priorities, expected outcome of changes and similar. 

![bg right:30%](images/01-laser.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kārlis Dambrāns (CC BY 2.0)" -->
## Quantifying risk
**Risk ~=**
**Consequences of bad thing * Probability**.  

Tsunami washing away Stockholm data center *
Probability of event ~= Extremely low risk.  

Customer data being stolen from EOL system *
Probability of event ~= Low-to-medium risk.  

![bg right:30%](images/01-door.jpg)
