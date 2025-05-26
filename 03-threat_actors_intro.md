---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Introduction to threat actors"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Introduction of threat actors and their motivations"
keywords:
  - "threat"
  - "intelligence"
  - "intel"
  - "ti"
  - "course"
  - "actor"
  - "motivations"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% David Revoy (CC BY 4.0)" -->
## Meet the threat actors

![bg right:30%](images/03-lighthouse.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% David Revoy (CC BY 4.0)" -->
## Why should we care?
Not all threat actors are created equal.  

Different motivations and expertise/resources.  

Tracking and understanding their activities may help us better protect ourselves.  
  
(and it's fun!)

![bg right:30%](images/03-lighthouse.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% David Revoy (CC BY 4.0)" -->
## Let's brasklapp!
Everyone has to live with
the "Internet noise".

Lots of hacking is opportunistic. 

![bg right:30%](images/03-lighthouse.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% David Revoy (CC BY 4.0)" -->
# Motivations
- Personal
- Financial
- Political
- Military

![bg right:30%](images/03-lighthouse.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
# Personal
- Curiosity / Learning
- Thrill seeking / Fun
- Fame / Cred
- Anger / Revenge

![bg right:30%](images/03-80s_room.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Asparukh Akanayev (CC BY 2.0)" -->
# Financial
- Industrial espionage
- Blackmail
- Stock / Market manipulation
- Computational resources

![bg right:30%](images/03-building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Theo Crazzolara (CC BY 2.0)" -->
# Political
- Intelligence gathering
- Propaganda
- Discrediting

![bg right:30%](images/03-strawberry_throne.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
# Military
- Intelligence gathering
- Disruption

![bg right:30%](images/03-missile_computer.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% David Revoy (CC BY 4.0)" -->
## Let's meet some of them!

![bg right:30%](images/03-lighthouse.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Stakkato
Swedish teenager hacking for
learning and the thrill.  
  
Targeted "high-security organisations"
and educational institutions.
  
While at the surface somewhat harmless,
how should we handle incident response?
  
(Curious to learn more? Check out
the old and cozy book ["Svenska hackare"](https://sv.wikipedia.org/wiki/Svenska_hackare)!)

![bg right:30%](images/03-80s_room.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## LulzSec
Small group of hackers with
"fun and mayhem" as their goals.

Targeted wide range of companies,
such as Sony Pictures, Fox News
and the game publisher Bethesda.

Disbanded after "50 days of lulz",
several members were later arrested
after group founder became informant.

While not the most technical and
quite opportunistic, good at PR!

![bg right:30%](images/03-80s_room.jpg)

<!--
https://www.youtube.com/watch?v=Op4gX7NwKj0
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Casey Umetsu
Sysadmin who was fired/made redundant.  
  
Allegedly used knowledge to disrupt
operations at former employer.
  
Malicious action by disgruntled employee
or an honest mistake using automation?
  
Useful lesson regardless!

![bg right:30%](images/03-80s_room.jpg)

<!--
https://www.bleepingcomputer.com/news/security/fired-admin-cripples-former-employers-network-using-old-credentials/
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Asparukh Akanayev (CC BY 2.0)" -->
## FIN7
Highly organised criminal group based in Russia.  
  
Focus on datatheft and "big-game" ransomware.  
  
Branched out into becoming a
"Ransomware as a Service" provider.

AKA _Carbon Spider_, _ELBRUS_ and _Sangria Tempest_,
depending on who you ask! :-/

![bg right:30%](images/03-building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Asparukh Akanayev (CC BY 2.0)" -->
## APT10
Chinese threat actor with focus on industrial espionage.  
  
Suspected ties to intelligence services.  
  
Responsible for the "Cloud Hopper" attacks
targeting (Swedish) MSPs.
  
This type of group is known as an
**A**dvanced **P**ersistent **T**hreat.

![bg right:30%](images/03-building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Asparukh Akanayev (CC BY 2.0)" -->
## Lazarus Group
Hacking group associated with the
North Korean government.  
  
Focus on attacks against payment services,
banking and cryptocurrency exchanges.
  
Known to use interesting tactics like
fake recruitment tests for developers
and getting hired for insider access.

![bg right:30%](images/03-building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Theo Crazzolara (CC BY 2.0)" -->
## Phineas Fisher
Highly skilled anarchist hacktivist.  
  
Targeted makers of "law enforcement spyware",
political parties and financial institutions.  
  
Claims to run "bug-bounty" for "ethical hacking".
  
Published surprisingly detailed write-ups of
hacking activities, providing useful lessons.

![bg right:30%](images/03-strawberry_throne.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Theo Crazzolara (CC BY 2.0)" -->
## Charming Kitten
State-sponsored Iranian group.  
  
Spies on various targets of interest to the government.
  
Targets organisations and individuals
(mainly dissidents and activists).

![bg right:30%](images/03-strawberry_throne.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Equation Group
Threat actor associated with NSA.  
  
Famous for malware such as "Stuxnet"
and "Flame".  
  
Targets adversaries of the USA.

Several tools associated with the group,
like an exploit for the "EternalBlue"
vulnerability, were stolen and leaked
by the threat actor "Shadow Brokers".

![bg right:30%](images/03-missile_computer.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Sandworm
Unit of the Russian military intelligence service.  
  
Known for disruptive attacks against the
Olympic Games and Ukrainian infrastructure.
  
While long known as a theoretical risk,
demonstrated attacks against a power grid.

(Check out [Andy Greenberg's book](https://www.goodreads.com/book/show/41436213-sandworm) if
you wanna learn more about them!)

![bg right:30%](images/03-missile_computer.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% David Revoy (CC BY 4.0)" -->
**Countless more for the interested!**

![bg right:30%](images/03-lighthouse.jpg)
