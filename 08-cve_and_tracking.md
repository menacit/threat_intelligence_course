---
SPDX-FileCopyrightText: © 2023 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: CVE and vulnerability tracking"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Presentation about CVE and vulnerability tracking for threat intelligence course"
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
## CVE and vulnerability tracking

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Background
Software has always contained bugs.  

Some of those are exploitable.  

Some software compontents are used in more than one product by more than one vendor.

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
_Can vulnerability X be exploited in vendor Y's software?_  

_Does our product have vulnerabilities similar to X?_  

_Can our IDS/vulnerability scanner detect vulnerability X?_  

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## What are "CVE IDs"?
Common Vulnerabilities and Exposures.  
  
Unique identifer assigned to vulnerabilities.  

Developed and managed by MITRE since 1999.
Over 200 000 flaws tracked in database so far.

Defacto industry standard used to track and talk about vulnerabilities.

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
**CVE-2022-47949**  

"CVE-" + \$Year + \$Sequence number

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
CVE IDs are in either the reserved, published or rejected state.  

At its core, a CVE entry contains a vulnerability description and a list of references.

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## How do I get one?
CVE IDs are allocated/assigned by a
CVE Numbering Authority (CNA).  

Each CNA is responsible for one or more vendors/products/software compontents.  

If software isn't covered by a CNA's scope, talk to a CNA-LR.

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Randy Adams (CC BY-SA 2.0)" -->
## CVE-2020-29583
> Firmware version 4.60 of Zyxel USG devices
> contains an undocumented account (zyfwp)
> with an unchangeable password. The
> password for this account can be found in
> cleartext in the firmware. This account
> can be used by someone to login to the
> ssh server or web interface with
> admin privileges.

![bg right:30%](images/08-abandoned_car.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## CVE-2021-22893
> Pulse Connect Secure 9.0R3/9.1R1 and higher
> is vulnerable to an authentication bypass
> vulnerability exposed by the Windows File
> Share Browser and Pulse Secure Collaboration
> features of Pulse Connect Secure that can
> allow an unauthenticated user to perform
> remote arbitrary code execution on the Pulse
> Connect Secure gateway. This vulnerability
> has been exploited in the wild.

![bg right:30%](images/08-oops_key.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Nacho Jorganes (CC BY-SA 2.0)" -->
## CVE-2016-5195
> Race condition in mm/gup.c in the Linux
> kernel 2.x through 4.x before 4.8.3 allows
> local users to gain privileges by leveraging
> incorrect handling of a copy-on-write (COW)
> feature to write to a read-only memory
> mapping, as exploited in the wild in
> October 2016, aka "Dirty COW."

![bg right:30%](images/08-cow.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Jack Lawrence (CC BY-SA 2.0)" -->
## CVE-2022-33637
> Microsoft Defender for Endpoint
> Tampering Vulnerability.

![bg right:30%](images/08-plastic_duck.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Edenpictures (CC BY 2.0)" -->
## CVE-2017-0144
> The SMBv1 server in Microsoft
> Windows Vista SP2;
> Windows Server 2008 SP2 and R2 SP1;
> Windows 7 SP1; Windows 8.1;
> Windows Server 2012 Gold
> and R2; Windows RT 8.1;
> and Windows 10 Gold, 1511, and 1607;
> and Windows Server 2016 allows
> remote attackers to execute
> arbitrary code via crafted packets,

![bg right:30%](images/08-wizard.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Making 'em more useful
Complementary information, such as severity ratings
and known affected products (CPEs),
is tracked in [NIST's NVD](https://nvd.nist.gov/).  

CISA's ["Known Exploited Vulnerabilities" (KEV)](https://www.cisa.gov/kev)
lists vulnerabilities that are know to have
been exploited by attackers.

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
Manually monitoring CVEs is time consuming.  

Tools like [OpenCVE](https://www.opencve.io)
can help you track and triage those relevant for your organisation.

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Ain't all roses
CNA is responsible for allocating CVE IDs and submitting description.  

Product vendors are often their own CNA.  

Not all vulnerabilities get assigned an ID :-/

![bg right:30%](images/08-difference_engine.jpg)
