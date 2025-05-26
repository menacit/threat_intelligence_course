---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Intrusion vocabulary"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Intrusion vocabulary presentation for threat intelligence course"
keywords:
  - "threat"
  - "intelligence"
  - "intel"
  - "ti"
  - "course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Mike Grauer Jr (CC BY 2.0)" -->
# Intrusion vocabulary
### A somewhat gentle introduction

![bg right:30%](images/07-abstract_wave.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Mike Grauer Jr (CC BY 2.0)" -->
We've begun to understand who we're protecting.  
  
We've gotten to know some of the threat actors.
  
We know that there is something called TTPs.
  
What does a "typical hack" look like?

![bg right:30%](images/07-abstract_wave.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Stig Nygaard (CC BY 2.0)" -->
## Overview of phases
- Reconnaissance
- Initial access
- Persistence
- Lateral movement / Privilege escalation
- Causing impact

![bg right:30%](images/07-goose.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Todd Van Hoosear (CC BY-SA 2.0)" -->
## Reconnaissance
Understanding the target organisation
and their attack surface.  

Active network scanning of exposed assets
and gathering of **O**pen **S**ource **Int**elligence.

Products in role descriptions on LinkedIn,
domains in certificate transparency logs,
paths/usernames in file metadata,
technical information leakage
in server headers...

(Mandatory plug for [Bellingcat](https://www.bellingcat.com/)!)

![bg right:30%](images/07-engine.jpg)

<!--
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Randy Adams (CC BY-SA 2.0)" -->
## Initial access
- (Spear) phishing / smishing / quishing...
- Credential stuffing / Password guessing
- Software bug exploitation

![bg right:30%](images/07-fisherman.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
## Persistence
Wanna be able to come and go as we please.  
  
Malware such as a **R**emote **A**ccess **T**rojan.  
  
Configuration of additional reset email addresses.
  
Backdooring of firmware if we're real serious!

![bg right:30%](images/07-gate.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kevin Dooley (CC BY 2.0)" -->
### Privilege escalation
Vertical escalation _("guest to admin rights")_
and horizontal escalation _("Org. A to Org. B")_.

### Lateral movement
Gain access to sensitive systems by exploiting
lacking segmentation and interconnectedness.

![bg right:30%](images/07-pipes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kārlis Dambrāns (CC BY 2.0)" -->
## Causing impact
- Disruption
- Data theft
- Defacement
- Resource hijacking

![bg right:30%](images/07-fire.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Andrew Pontzen / Fabio Governato (CC BY 2.0)" -->
During all the phases, we might put
some effort into covering our tracks
and "muddy the waters" to make
attribution more difficult.

Delete (some) audit log events,
utilise proxy/tunneling services,
modify locale metadata in malware,
avoid hacking during "working hours"...

![bg right:30%](images/07-universe_light_distribution.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Guilhem Vellut (CC BY 2.0)" -->
Wanna dig deeper into the phases of a hack
and discover known TTPs of threat actors?  

Have a look at [MITRE ATT&CK](https://attack.mitre.org/groups/).

![bg right:30%](images/07-mouxy_abandoned_house.jpg)

<!--
https://attack.mitre.org/groups/G1017/ / Volt Typhoon is decent example
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Stig Nygaard (CC BY 2.0)" -->
Some are trying to name and define
the phases of a hacking campaign in a
standardised way, with more or less success.

Lockheed Martin's ["Cyber Kill Chain"](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html)
is a commonly used example.

![bg right:30%](images/07-el_salvador_mountain.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Mike Grauer Jr (CC BY 2.0)" -->
## Wrapping up

![bg right:30%](images/07-abstract_wave.jpg)

