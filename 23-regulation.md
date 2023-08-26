---
SPDX-FileCopyrightText: © 2023 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Rules and regulations"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Presentation about impact of rules/regulations in threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Rules and regulation
### (Seen by some as a threat)

![bg right:30%](images/23-typewriter.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
We've mostly focused on keeping up with activities of threat actors.  
  
Other developments can greatly affect how organizations prioritize their security efforts.  

Let's talk a bit about  
**regulation** and **compliance frameworks**.

![bg right:30%](images/23-typewriter.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Bruno Cordioli (CC BY 2.0)" -->
- GDPR
- NIS(2)
- PSD2
- FIPS
- PCI DSS
- ISO 27K / SOC 2

![bg right:30%](images/23-capsule_house.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
## GDPR
**G**eneral **D**ata **P**rotection **R**egulation.  
  
Attempt to unify and strengthen privacy
for individuals within the EU + EEA.  

Translate into member state law
and enforced since 2018 by
**D**ata **P**rotection **A**uthorities.

![bg right:30%](images/23-chip.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
## Protecting what?
Privacy of **natural/physical persons**
(temporarily) located in the EU. 
  
More specifically, protection of **P**ersonal **D**ata
(AKA **P**ersonally **I**dentifiable **I**nformation).

**P**ersonal **D**ata is (according to the GDPR)
anything that can be tied to the activities of
an individual.

![bg right:30%](images/23-chip.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
### Personal Data
Physical/digital addresses, gender, ID number,
location information, phone number,
date of birth, photographs...

### Sensitive Personal Data
Race/ethnicity, political opinions/affiliations,
religious/philosophical beliefs, union membership,
Sexual preferences/activities and
health/medical information.

![bg right:30%](images/23-chip.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
### Individuals have the right to...
1. Be informed
2. Access
3. Rectification
4. Object processing

![bg right:30%](images/23-chip.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
### Individuals have the right to...
5. Avoid/restrict automated profiling
6. Be forgotten
7. Data portability
8. Restrict processing

![bg right:30%](images/23-chip.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
### Consequences
Organization must document how they
store, process and protect PD.
  
They must also assign a
**D**ata **P**rotection **O**fficer\*.

Failure to respect individuals' rights or
inadequate protection of PD could result in
large sanction fees (200 MSEK || 4% of revenue)
and other forms of punishment.

![bg right:30%](images/23-chip.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
## Enforcement in Sweden
**I**ntigritetsskydds**my**ndigheten
(previously called **D**ata**i**nspektionen) is the DPA.  

~120 employees, slowly growing.

| Year | Fees in SEK | Number of fees |
|------|-------------|----------------|
| 2018 | 0           | 0              |
| 2019 | 500 000     | 2              |
| 2020 | 150 000 000 | 15             |
| 2021 | 32 500 000  | 7              |
| 2022 | 9 720 000   | 4              |


![bg right:30%](images/23-chip.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Manfred Werner (CC BY-SA 3.0)" -->
## EU and USA
GDPR limits transfer of PD to
_third countries_.  
  
In practice, tons of (S)PD is collected
and processed in the USA.  
  
When (and if at all) this is okay is a
constant back and forth.

![bg right:30%](images/23-schrems.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Johannes P1hde (CC BY 2.0)" -->
## Example: [Data transfer fine](https://gdprhub.eu/index.php?curid=5944)

![bg right:30%](images/23-ccc.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% ESA (CC BY-SA 3.0 IGO)" -->
## Example: [Employee monitoring](https://gdprhub.eu/index.php?curid=2751)

![bg right:30%](images/23-abstract_fields.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Ted Eytan (CC BY-SA 2.0)" -->
## Example: [Google school ban](https://gdprhub.eu/index.php?curid=5093)

![bg right:30%](images/23-flowers.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Tom Held (CC BY 2.0)" -->
## Example: [Inadequate protection](https://gdprhub.eu/index.php?curid=2820)

![bg right:30%](images/23-pcb.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Example: [Unlawful marketing](https://gdprhub.eu/index.php?curid=6105)

![bg right:30%](images/23-retro_computer.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Crazy Crusty (CC0 1.0)" -->
## Example: [Not just giants](https://gdprhub.eu/index.php?curid=2601)

![bg right:30%](images/23-gas_mask.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Bruno Cordioli (CC BY 2.0)" -->
For more examples and details, check out  
**[GDPRhub](https://gdprhub.eu/)**.

![bg right:30%](images/23-macintosh_plus.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Todd Van Hoosear (CC BY-SA 2.0)" -->
## NIS(2)
**N**etwork and **I**nformation **S**ecurity Directive.
  
Aims to ensure availability of services and infrastructure critical to society.  
  
Initially released in 2018, version 2
shall be enforced by member states in 2024.

![bg right:30%](images/23-tower.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Todd Van Hoosear (CC BY-SA 2.0)" -->
## What does that mean?
Organizations must structure and document their IT security efforts.  

Security efforts must be
_appropriate to the risk posed_,
as interpreted by the **sector regulator**.

If an incident occurs, it must be reported to
the sector regulator within 6 hours. 

Failure to comply can result in
sanction fees (10 MSEK || 2% of revenue)
and other consequences.

![bg right:30%](images/23-tower.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Todd Van Hoosear (CC BY-SA 2.0)" -->
## Critical sectors

### Version 1
Banking/payment services, digital infrastructure,
Energy, healthcare and logistics/transportation.

### Version 2
Food production/distribution, waste treatment,
central heating/cooling, "heavy industry",
local/national "authorities", postal services
and (aero)space.

![bg right:30%](images/23-tower.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Todd Van Hoosear (CC BY-SA 2.0)" -->
Is our organization providing
services critical to society?  
  
Well, that's up to the sector regulator.

![bg right:30%](images/23-tower.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kevin Dooley (CC BY 2.0)" -->
## PSD2
**P**ayment **S**ervices **D**irective.  

Aims to increase innovation and competition
within payment/banking sector.

Among other things, forces banks to open up
their online services (APIs) to third-parties.  

While not focused on security,
it surely affects it.

![bg right:30%](images/23-cemetery.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Wolfgang Stief (CC0 1.0)" -->
## FIPS
**F**ederal **I**nformation **P**rocessing **S**tandards.

Published by [NIST](https://en.wikipedia.org/wiki/National_Institute_of_Standards_and_Technology),
describes things such as acceptable encryption algorithms and other security related requirements.

US government/military enforces FIPS during procurement.

![bg right:30%](images/23-pdp_11.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## PCI DSS
**P**ayment **C**ard **I**ndustry
**D**ata **S**ecurity **S**tandard.
  
Specifies technical and organizational
security requirements.
  
Requires yearly audit by an external
**Q**ualified **S**ecurity **A**ssessor.
  
If you want to handle card numbers,
you need to comply.

![bg right:30%](images/23-cogwheels.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Jan Helebrant (CC0 1.0)"-->
## ISO 27K / SOC 2
The ISO 27000-family of standards describes
methods for organizations to structure
their security efforts.  

Identified risks must be
evaluated, documented and acted upon.  

Many organizations require that their vendors/partners are ISO 27001 certified.  

SOC 2 is basically the equivalent thing in the USA.

![bg right:30%](images/23-ancient_stairs.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Jan Helebrant (CC0 1.0)"-->
While rules/regulations serve different purposes,
they warrant a response more often than not.  

Especially since interpretation and enforcement may change over time.

![bg right:30%](images/23-observatory.jpg)
