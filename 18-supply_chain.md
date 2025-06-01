---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: Software supply chain"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Understanding the role of software supply chain in threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Axelspace Corporation (CC BY-SA 4.0)" -->
## Software supply chain
### Dependencies and imported risk

![bg right:30%](images/18-suez_canal_satellite.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Axelspace Corporation (CC BY-SA 4.0)" -->
No one builds computers from scratch.  
  
Relies on a highly interconnected
and globalized supply chain.
  
Risk VS Reward.

![bg right:30%](images/18-suez_canal_satellite.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Chris 73 (CC BY-SA 3.0)" -->
**Likewise,
no one builds software from scratch.**

![bg right:30%](images/18-grey_archive_racks.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Example: Keycloak server
Popular solution for identity and access
management - an authentication service.  

```
$ mvn clean install | tee build_output.txt

[...]
Downloaded from central:
https://repo.maven.apache.org/maven2/org/
fusesource/jansi/jansi/1.16/jansi-1.16.jar
[...]

$ grep \
  -E 'Downloaded from central: .+\.jar' \
  build_output.txt | wc --lines

1465
```

![bg right:30%](images/18-punch_tape.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## What's the problem?

![bg right:30%](images/18-c64.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Miguel Discart (CC BY-SA 2.0)" -->
## XZ Utils backdoor
Freely available code library for handling
LZMA data compression ("liblzma").  

Great example of something (boring) that
people wanna avoid writing from scratch.  

Included in countless code-bases
(both proprietary and open-source),
for example **systemd**...

![bg right:30%](images/18-gas_mask.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Miguel Discart (CC BY-SA 2.0)" -->
## XZ Utils backdoor
In March of 2024, malicious code was
detected in the software library that
targeted the widely deployed
OpenSSH server process.  

The code introduced a backdoor,
allowing attackers with a secret key
to remotely access the vulnerable system.  

The backdoor code was included by one of
the maintainers of XZ Utils.

![bg right:30%](images/18-gas_mask.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Fredrik Rubensson (CC BY-SA 2.0)" -->
## Log4Shell
Vulnerability in popular Java logging library
"Log4j" (CVE-2021-44228).  

Could be exploited by injecting code in messages that were logged (CVSS 10.0).  

![bg right:30%](images/18-log_on_log.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Kevin L Neff (CC BY 2.0)" -->
Not just a problem affecting freely
available open source libraries...

![bg right:30%](images/18-propane_torch_soldering.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Nirvana Studios (CC BY 4.0)" -->
## Root cause analysis
The initial cost of including
third-party libraries is near zero.  
  
Dependencies often have their own dependencies.  
  
Maintaining software over time ain't always
the most fun/rewarding task, especially for free.  
  
Your security depends on the security of
your dependencies and that of its developers.

![bg right:30%](images/18-installation_the_singularity.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Nirvana Studios (CC BY 4.0)" -->
## [XKCD #2347: Dependency](https://xkcd.com/2347/)

![bg right:30%](images/18-installation_the_singularity.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Tobin (CC BY-SA 2.0)" -->
(**S**oftware) **B**ill **O**f **M**aterials.  
  
Term borrowed from physical manufacturing.
Describes components (and their suppliers)
required to assemble a product.  
  
Helps us understand what/who our software
relies on and what/who we need to monitor.
  
Several competing standards exist,
like [CycloneDX](https://cyclonedx.org/) and [SPDX](https://spdx.dev/).  
  
Also useful for license compliance.
  
Tools exist to generate SBOMs using
source code analysis and guesstimation.

![bg right:30%](images/18-pcb.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Axelspace Corporation (CC BY-SA 4.0)" -->
## Conclusions
Should I really depend on
third-party code?  
  
In the end of the day,
it's all a cost-benefit gamble.  

Automated dependency monitoring,
[OpenSSF Scorecard](https://openssf.org/projects/scorecard/) reviews and
similar efforts can minimize the risk.

![bg right:30%](images/18-suez_canal_satellite.jpg)
