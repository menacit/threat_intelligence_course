---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: CVSS basics"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Introduction to CVSS for threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
# CVSS basics
### Common Vulnerability Scoring System 

![bg right:30%](images/09-computer.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Background
CVE IDs tell us that a vulnerability exist.  
  
Its description doesn't necessarily tell us
the potential impact or if there are any
prerequisites for exploitation.  
  
Great need for a common method to rate and
compare severity of vulnerabilities.

![bg right:30%](images/09-computer.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Loco Steve (CC BY-SA 2.0)" -->
The **C**ommon **V**ulnerability **S**coring **S**ystem
aims to provide a solution.
  
Standard developed by [FIRST](https://www.first.org/) to describe
the "characteristics of a vulnerability".  
  
Widely used to guide and prioritize
vulnerability remediation efforts.

![bg right:30%](images/09-allen_gardens_street_art.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
Produces a numerical score between 0.0 and 10.0.

Vulnerabilities may be assigned a textual
severity rating based on their score:

| **Severity** | **Numerical score range**  |
|--------------|----------------------------|
| None         | 0.0                        |
| Low          | 0.1 - 3.9                  |
| Medium       | 4.0 - 6.9                  |
| High         | 7.0 - 8.9                  |
| Critical     | 9.0 - 10.0                 |

![bg right:30%](images/09-sunken_house_boat.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
CVSS "vector strings" provide a compact way to
communicate the reasoning behind a score:

```
CVSS:4.0/AV:N/AC:L/AT:N/PR:L ↴
/UI:P/VC:H/VI:L/VA:L/SC:N/SI:N/SA:N
```

(We shall cover this later, don't worry!)

![bg right:30%](images/09-sunken_house_boat.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Loco Steve (CC BY-SA 2.0)" -->
Several different versions exist,
4.0 was release in late 2023.  
  
Version 3.1 is still most commonly used.  
  
Available as a formal specification or
through a handy [online calculator tool](https://www.first.org/cvss/calculator/4-0).
  
(If you're paranoid, consider using
a local copy of the calculator!)

![bg right:30%](images/09-brick_lane_sculpture.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Let there be demos!

![bg right:30%](images/09-computer.jpg)
