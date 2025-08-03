---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Source analysis"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Presentation about source analysis/criticism in threat intelligence course"
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

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kurayba (CC BY-SA 2.0)" -->
## Source analysis
### Critical parsing of intelligence

![bg right:30%](images/25-cave_stairs.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kurayba (CC BY-SA 2.0)" -->
Most organisations rely on third-party
sources to provide threat intelligence.

Lots out there with widely different quality.

Let's look at some considerations
before relying on it, shall we?

![bg right:30%](images/25-cave_stairs.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
## Source categories
- First-party producers
- Free / Public aggregators
- Paid / Private aggregators

![bg right:30%](images/25-painted_brick_wall_with_holes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
Some examples, perhaps?

![bg right:30%](images/25-painted_brick_wall_with_holes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Oklahoma National Guard (CC BY 2.0)" -->
## First-party producers
- Victims
- Security companies/vendors
- Journalists
- Governmental organisations

![bg right:30%](images/25-rappelling_worker.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Dennis van Zuijlekom (CC BY-SA 2.0)" -->
## Victims
Straight from the horse's mouth!
  
Crisis management and/or legal requirement
(_privacy laws, financial reports, court cases_).
  
Beware of spin and lacking expertise.

![bg right:30%](images/25-broken_hdd.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Austin Design (CC BY-SA 2.0)" -->
## Security companies/vendors
Most intelligence are provided by
commercial cybersecurity actors.
  
Original research or analysis from
incident responses efforts.
  
Often high quality.
  
Ask yourself what they're selling.

![bg right:30%](images/25-smokey_man.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Jan Hrdina (CC BY-SA 2.0)" -->
## Journalists
_\<INSERT EVERYTHING GREAT ABOUT
PROFESSIONAL JOURNALISM HERE\>_
  
May provide the "attacker's perspective".
  
Severe lack of technical competency
and often sensationalist.

![bg right:30%](images/25-optics.jpg)

<!--
Examples:
- https://krebsonsecurity.com/2024/11/an-interview-with-the-target-home-depot-hacker/
- https://goodreads.com/book/show/18509663-spam-nation
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Richard James (CC BY 2.0)" -->
## Governmental organisations
Allegedly have access to high-quality and
non-publicly available information.

Spying, surveillance and reporting requirements.

Unfortunately a lot of "trust me, bro".

Shouldn't be discarded, but meditate upon
possible alternative motives.

![bg right:30%](images/25-lembit_periscope.jpg)

<!--
Example: https://en.wikipedia.org/wiki/Concerns_over_Chinese_involvement_in_5G_wireless_networks
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Adam Lusch (CC BY-SA 2.0)" -->
## Free / Public aggregators
- Academic research
- Think Tanks / NGOs
- Community threat feeds

![bg right:30%](images/25-hudson_yards.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% FoAM (CC BY-SA 2.0)" -->
### Academic research
Hopefully provides high-quality analysis.
  
Often lack relevant "educated guesses".

### Think Tanks / NGOs
Provides "hot-takes", "other perspectives"
"interesting correlations"...
  
Beware of their agenda, biases and funding.
  
(_Often used in **PS**ychological **OP**erations._)

![bg right:30%](images/25-cardboard_city_colors.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Cory Doctorow (CC BY-SA 2.0)" -->
## Community threat feeds
(Automatically) collects, normalises and
publish IoCs from other sources.
  
Shared effort, inexpensive for consumers.
  
Highly-variable quality, significant
risk of "false-positives".

![bg right:30%](images/25-houses_art.jpg)

<!--
Example: https://github.com/stamparm/ipsum
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% D. Essl / ESO (CC BY 4.0)" -->
What about paid / private aggregators?

![bg right:30%](images/25-eso_headquarters_fish_eye.jpg.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Holger Ellgaard (CC BY-SA 4.0)" -->
## ISACs
**I**nformation **S**haring and **A**nalysis **C**enters
exist to support specific private/public
sectors and interest areas.
  
Defense alliances, telecom, financial services...
  
Highly intelligence with less fear
of "tipping off" threat actors.

May have "sharing requirements".
  
Tricky to draw generalised conclusions
regarding quality and biases.

![bg right:30%](images/25-forsmark_road_entry.jpg)

<!--
Examples:
- https://en.wikipedia.org/wiki/Information_Sharing_and_Analysis_Center
- https://www.fsisac.com/
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Elly Jonez (CC BY 2.0)" -->
## Commercial providers
Sells (original) research and aggregations
through a "subscription" model.

Adds value by normalising/categorising data.
  
Many produce targeted reports per request.
  
Often expensive, sometimes high quality.

![bg right:30%](images/25-window_computer.jpg)

<!--
Example of commercial vendor: https://www.recordedfuture.com/
-->

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Stig Nygaard (CC BY 2.0)" -->
## Wrapping up

![bg right:30%](images/25-little_gunver.jpg)
