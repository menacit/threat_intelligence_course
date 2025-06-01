---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Protecting what?"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Presentation about attack surface management for threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Solarbotics (CC BY 2.0)" -->
# Protecting what?
### Managing your attack surface

![bg right:30%](images/17-reservoir_model.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Solarbotics (CC BY 2.0)" -->
## Quick recap
Assets exposed towards threat actors
that may be attacked.  

The attack surface may not look
the same to all threat actors.

Keeping track of systems in
your IT environment is key!

![bg right:30%](images/17-reservoir_model.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Pyntofmyld (CC BY 2.0)" -->
## How about a CMDB?
**C**onfiguration **M**anagement **D**ata**b**ase.  
  
Tool for documenting HW- and/or SW-assets.  
Excel spreadsheet or fully-fledged application.
  
Stores related information like system owners
and their relationships/dependencies.
  
Often aims to provide a **S**ingle **S**ource **o**f **T**ruth.
  
Use the information to configure monitoring
of specific CPEs in the CVE database...

![bg right:30%](images/17-pdp11.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Pyntofmyld (CC BY 2.0)" -->
## Sounds simple enough?

![bg right:30%](images/17-pdp11.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Theo Crazzolara (CC BY 2.0)" -->
Manual documentation always\* drift
from reality over time.  

Documentation tends to be sacrificed
first during stress/pressure.  

Faulty/Outdated documentation may
be worse than not having any.

![bg right:30%](images/17-bird.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Theo Crazzolara (CC BY 2.0)" -->
## All doom and gloom?

![bg right:30%](images/17-bird.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Wolfgang Stief (CC0 1.0)" -->
## IaC and automation
Automation tools, such as Terraform,
Ansible and CI/CD pipelines,
are "self-documenting".  
  
_(rant about incident recovery)_
  
Only works if _ClickOps_ is
disallowed/heavily restricted.

![bg right:30%](images/17-tapes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Randy Adams (CC BY-SA 2.0)" -->
## Using the hacker toolbox
DNS zone dumping/enumeration.  
  
Network and service scanning tools,
such as [Nmap](https://nmap.org/) and [Shodan](https://nmap.org/).  
  
Application fingerprinting with tools like [WhatWeb](https://github.com/urbanadventurer/WhatWeb).  
  
Querying of cloud platform APIs.  
  
Purpose built software like [runZero](https://www.runzero.com/).
  
Product category: **A**ttack **S**urface **M**anagement.

![bg right:30%](images/17-abstract_pattern.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Randy Adams (CC BY-SA 2.0)" -->
Perhaps an agent like [osquery](https://osquery.io) may be useful?

```sql
SELECT name, version FROM chrome_extensions 
WHERE name LIKE "%Netflix%";

+-----------------------+---------+
| name                  | version |
+-----------------------+---------+
| Netflix Party         | 1.0.4   |
+-----------------------+---------+
| US Netflix Anywhere   | 0.2.7   |
+-----------------------+---------+
```

Deploy it to your servers and end-points
to gain insights unavailable through
simple network scanning.

![bg right:30%](images/17-abstract_pattern.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Solarbotics (CC BY 2.0)" -->
## Wrapping up
Understanding your IT environment and
attack surfaces may help you focus
gathering of threat intelligence.
  
Sadly, it is rarely well documented.
  
In most organisations, you'll likely need
to utilize all three methods described.

![bg right:30%](images/17-reservoir_model.jpg)
