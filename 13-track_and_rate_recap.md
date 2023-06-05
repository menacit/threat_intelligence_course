---
SPDX-FileCopyrightText: © 2023 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: CVE/CVSS recap"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Recap about CVE and CVSS for threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Edenpictures (CC BY 2.0)" -->
# CVE/CVSS recap
### Tracking and rating vulnerabilities

![bg right:30%](images/13-building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## CVE
Common Vulnerabilities and Exposures.  
  
Unique identifer assigned to vulnerabilities.  

"CVE-" + \$Year + \$Sequence number

![bg right:30%](images/13-random_numbers.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
## CVSS
Common Vulnerability Scoring System.  

Describes the "characteristics of a vulnerability".  
Widely used to guide and prioritize remidiation efforts.  

The base rating can be tweaked using
"temporal" and environmental" scores.

![bg right:30%](images/13-crack.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
## CVSS
| **Severity** | **Base score** |
|--------------|----------------|
| None         | 0.0            |
| Low          | 0.1 - 3.9      |
| Medium       | 4.0 - 6.9      |
| High         | 7.0 - 8.9      |
| Critical     | 9.0 - 10.0     |

![bg right:30%](images/13-crack.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
Information, such as severity ratings
and known affected products (CPEs),
is tracked in [NIST's NVD](https://nvd.nist.gov/).  

CISA's ["Known Exploited Vulnerabilities" (KEV)](https://www.cisa.gov/kev)
lists vulnerabilities that are know to have
been exploited by attackers.

![bg right:30%](images/13-punch_tape.jpg)

