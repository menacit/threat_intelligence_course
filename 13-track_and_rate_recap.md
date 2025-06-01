---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
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

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Edenpictures (CC BY 2.0)" -->
# CVE / CVSS recap
### Tracking and rating vulnerabilities

![bg right:30%](images/13-building.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
**C**ommon **V**ulnerabilities and **E**xposures.  
  
Unique identifier assigned to a vulnerability
in a software component.
  
Used to track flaws and communicate about them.  
  
Managed by MITRE and
**C**VE **N**umbering **A**uthorities (often vendors).  
  
"CVE-" + \$Year + \$Sequence number

![bg right:30%](images/13-random_numbers.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Adam Lusch (CC BY-SA 2.0)" -->
We can tie other useful information to CVE IDs!
  
**C**ommon **P**latform **E**numeration
provides as structured/computer-readable
format to describes which vendors, products
and software versions are affected by a flaw.
  
**C**ommon **W**eakness **E**numeration
provides a list of common vulnerability
types that may affect software/hardware.

![bg right:30%](images/13-demolition_pigeon.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Darkday (CC BY 2.0)" -->
The **K**nown **E**xploited **V**ulnerabilities
list contains flaws that they've identified
being actively exploited by threat actors.

The **E**xploit **P**rediction **S**coring **S**ystem
and **L**ikely **E**xploited **V**ulnerabilities
aim to predict how likely it is that a flaw
will actually be exploited in "the wild".

![bg right:30%](images/13-burnt_and_abandoned_computer.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
**C**ommon **V**ulnerability **S**coring **S**ystem.  
  
Used to calculate severity rating and
describe the "characteristics of a vulnerability".  
  
Widely used to prioritize remediation efforts.
  
Can adapt rating based on a specific
organisation's implementation/requirements
using "environmental metrics".
  
"Threat metrics" can be added to
indicate availability of exploits.

![bg right:30%](images/13-crack.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brendan J (CC BY 2.0)" -->
| **Severity** | **Base score** |
|--------------|----------------|
| None         | 0.0            |
| Low          | 0.1 - 3.9      |
| Medium       | 4.0 - 6.9      |
| High         | 7.0 - 8.9      |
| Critical     | 9.0 - 10.0     |

### Vector string
```
CVSS:4.0/AV:N/AC:L/AT:N/PR:L ↴
/UI:P/VC:H/VI:L/VA:L/SC:N/SI:N/SA:N
```

![bg right:30%](images/13-crack.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
Ready to move forward?

![bg right:30%](images/13-punch_tape.jpg)
