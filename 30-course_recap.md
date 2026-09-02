---
SPDX-FileCopyrightText: © 2026 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Course recap"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Recap of what has been covered in the threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Luis Zuno (CC0 1.0)" -->
# Course recap

![bg right:30%](images/30-pixel_mountain.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Luis Zuno (CC0 1.0)" -->
## Let us recap...
- Asset and attack surface management
- Software supply chain security
- **I**ndicators **o**f **C**ompromise
- Regulation and compliance frameworks

![bg right:30%](images/30-pixel_mountain.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Cory Doctorow (CC BY-SA 2.0)" -->
## Managing assets/attack surface
Understand what threat actors could
try to attack - larger attack surface
means greater risk that they get in!\*

To help us, let's lean upon:
- **C**onfiguration **M**anagement **D**ata**b**ase.
- **I**nfrastructure **a**s **C**ode,
- Active scanning (_"Hacker's toolbox"_).

Tells us what to focus on during
intelligence gathering (CPEs, etc.).

![bg right:30%](images/30-trunk_skeleton.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Fritzchens Fritz (CC0 1.0)" -->
## Supply chain security
Most applications utilize third-party
code libraries for (boring) functionality.

Dependencies have their own dependencies.
  
May contain (intentional) vulnerabilities,
backdoors and other malicious things.

Utilize **S**oftware **B**ill **o**f **M**aterials
files to keep track of these.

![bg right:30%](images/30-abstract_chip.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Andrew Hart (CC BY-SA 2.0)" -->
## Indicators of Compromise
Used to improve **I**ntrusion **D**etection /
**P**revention **S**ystems and used for attribution.  

IP addresses, domain names, file hashes,
URL paths, traffic patterns...

Low-level threat sharing!

![bg right:30%](images/30-broken_glass.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kojach (CC BY 2.0)" -->
## Rules and regulations
- GDPR
- NIS(2)
- DORA
- CRA
- PSD2
- FIPS
- PCI DSS
- ISO 27K / SOC 2

![bg right:30%](images/30-punch_cards.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Steve Jurvetson (CC BY 2.0)" -->
## GDPR
Attempt to strengthen individuals' privacy
through its "eight rights" since 2018.

Restricts how organizations may store/use
**P**ersonal **D**ata (AKA **PII**).

Some of is considered extra sensitive:

> Race/ethnicity, political opinions/affiliations,
> religious/philosophical beliefs,
> union membership,
> sexual preferences/activities
> and health/medical information.

![bg right:30%](images/30-drones.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Steve Jurvetson (CC BY 2.0)" -->
## GDPR
Organizations handling PD must appoint a
**D**ata **P**rotection **O**fficer\*.

Each EEA member state has at least one
**D**ata **P**rotection **A**uthority that
_should_ ensure compliance - **IMY** in Sweden.

Failure to respect individuals' rights or
inadequate protection of PD could result in
sanction fees (200 MSEK || 4% of revenue)
and other forms of punishment.

![bg right:30%](images/30-drones.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Halfrain (CC BY-SA 2.0)" -->
## NIS(2)
Aims to ensure availability of services
and infrastructure critical to society,
baked into "Cybersäkerhetslagen".

Strict process and reporting requirements.

Security efforts must be
_appropriate to the risk posed_,
as interpreted by the **sector regulator**.

Failure to comply can result in
sanction fees (10 MSEK || 2% of revenue)
and other consequences.

![bg right:30%](images/30-tripple_exposure_road_2.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Halfrain (CC BY-SA 2.0)" -->
## NIS(2)

### Version 1
Banking/payment services, digital infrastructure,
Energy, healthcare and logistics/transportation.

### Version 2
Food production/distribution, waste treatment,
central heating/cooling, "heavy industry",
local/national "authorities", postal services
and (aero)space.

![bg right:30%](images/30-tripple_exposure_road_2.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Quinn Dombrowski (CC BY-SA 2.0)" -->
### DORA
Aims to strengthen cyber resilience of
"financial entities" (banks, PSPs, etc).

Large overlap with NIS2, but stricter
guidance for _realistic_ security testing.

### CRA
Upcoming regulation that aims to
improve security of "digital" products
and services sold in the EU.

Secure defaults, dependency tracking,
vulnerability patching, auditing...
(depending on [product category](https://craevidence.com/cra-compliance/product-classification))

![bg right:30%](images/30-switches.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kenny Cole (CC BY 2.0)" -->
## PSD2
Aims to increase innovation and competition
within payment/banking sector.

Among other things, forces banks to open up
their online services (APIs) to third-parties.  

While not focused on security,
it surely affects it.

![bg right:30%](images/30-penguins.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Cory Doctorow (CC BY-SA 2.0)" -->
### FIPS
(Security related) standards
published by NIST.

If you wanna sell something to government
entities in the USA, make sure to comply!

### PCI DSS
Specifies technical and organizational
security requirements for those that
want to handle credit/debit cards.

Requires yearly audit by an external
**Q**ualified **S**ecurity **A**ssessor.

![bg right:30%](images/30-clouds.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Sergei Gussev (CC BY 2.0)" -->
### ISO 27001
Certified organizations must structure and
document their (resonable) security efforts.

Identified risks must be evaluated,
documented and acted upon.

### SOC 2
Basically the same the thing for Yankees. 
Longer/more expensive audit process.

![bg right:30%](images/30-singapore_1.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Nicholas A. Tonelli (CC BY 2.0)" -->
**That's it! Everything clear?**

![bg right:30%](images/30-abandoned_chimney.jpg)
