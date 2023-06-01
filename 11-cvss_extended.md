---
SPDX-FileCopyrightText: © 2023 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Extending CVSS"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Presentation about advanced usage of CVSS for threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Pedro Mendes (CC BY-SA 2.0)" -->
## Advanced CVSS usage
### Temporal and environmental metrics

![bg right:30%](images/11-arecibo.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Pedro Mendes (CC BY-SA 2.0)" -->
## The problem
In practice, the urgency to mitigate a vulnerability may change over time.  

Is it just theoretically exploitable or are there public Metasploit modules circulating?  

Are there any factors that affect the severity for my particular usecase?

![bg right:30%](images/11-arecibo.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Pedro Mendes (CC BY-SA 2.0)" -->
The **temporal** and **environmental** scores exist to solve the problem.

![bg right:30%](images/11-arecibo.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Pedro Mendes (CC BY-SA 2.0)" -->
# Let there be demos!

![bg right:30%](images/11-arecibo.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Pedro Mendes (CC BY-SA 2.0)" -->
## Taking it further
FIRST provides a complementary tool called
["The Exploit Prediction Scoring System" (EPSS)](https://www.first.org/epss/).  

Uses ~~machine learning and voodoo magic~~
sophisticated prediction models to guesstimate
how likely it is that a flaw will be
practically exploitable.  

Currently provided as API with scores for all published CVEs. Use with caution.

![bg right:30%](images/11-arecibo.jpg)

