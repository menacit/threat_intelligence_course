---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
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
Software will always contain bugs.  
  
Some of those are exploitable.  
  
Some software components are used in more
than one product by more than one vendor
(think popular libraries like [OpenSSL](https://www.openssl.org/)).

![bg right:30%](images/08-difference_engine.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Rod Waddington (CC BY-SA 2.0)" -->
_Is vendor Y's software affected by vulnerability X?_  
  
_Does our product have vulnerabilities similar to X?_  
  
_Can our **I**ntrusion **D**etection **S**ystem
identify attempts to exploit vulnerability X?_  
  
_Can our vulnerability scanner detect X?_

![bg right:30%](images/08-mauritius.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Stig Nygaard (CC BY 2.0)" -->
## What are "CVE IDs"?
**C**ommon **V**ulnerabilities and **E**xposures.  
  
Unique identifier assigned to vulnerabilities.  

Developed and managed by [MITRE](https://www.mitre.org/) since 1999.
Over 280000 flaws registered in the database.

Defacto industry standard used to track
and talk about vulnerabilities.

![bg right:30%](images/08-glowing_fish.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Stig Nygaard (CC BY 2.0)" -->
**CVE-2022-47949**  

"CVE-" + \$Year + \$Sequence number

![bg right:30%](images/08-glowing_fish.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Stig Nygaard (CC BY 2.0)" -->
CVE IDs are in either the "reserved",
"published" or "rejected" state.  

At its core, a CVE database entry contains
a vulnerability description and optionally
a list of references (external links).

![bg right:30%](images/08-kullen.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Loco Steve (CC BY-SA 2.0)" -->
## How do I get one?
CVE IDs are allocated/assigned by a
**C**VE **N**umbering **A**uthority.  

Each CNA is responsible for one or more
vendors/products/software components.  

If the software isn't covered by the
scope of any existing CNA, talk to a
CNA of **L**ast **R**esort (CNA-LR).

![bg right:30%](images/08-big_ben.jpg)

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
<!-- _footer: "%ATTRIBUTION_PREFIX% Stig Nygaard (CC BY 2.0)" -->
There are "extensions" to the CVE database
that may be used to associate additional
useful information to an identifier.
  
Some are created/managed by MITRE,
others by third-parties.

Let's have a look at the most common ones...

![bg right:30%](images/08-curly_purple.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Egill Egilsson (CC BY 2.0)" -->
**C**ommon **P**latform **E**numeration
provides as structured/computer-readable
format to describes which vendors, products
and software versions are affected by a flaw.
  
`cpe:2.3:a:ivanti:endpoint_manager_mobile:12.5`
  
The [page about CPE on Wikipedia](https://en.wikipedia.org/wiki/Common_Platform_Enumeration) provides
a decent explanation of the sub-fields.

![bg right:30%](images/08-esbjerg.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Adam Lusch (CC BY-SA 2.0)" -->
**C**ommon **W**eakness **E**numeration
provides a list of common vulnerability
types that may affect software/hardware.

Similar to [OWASP Top Ten](https://owasp.org/www-project-top-ten/), but more generic.

Useful as reference for flaw mitigation
and to understand historic security
challenges in codebase.

Who could forget classics like
[CWE-416 _(AKA "Use After Free")_](https://cwe.mitre.org/data/definitions/416.html) and
[CWE-89 _(AKA "Improper Neutralization of Special Elements used in an SQL Command")_](https://cwe.mitre.org/data/definitions/89.html) ?!

![bg right:30%](images/08-parallel_pipes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% ESA (CC BY-SA 3.0 IGO)" -->
The USA's **C**ybersecurity and
**I**nfrastructure **S**ecurity **A**gency
maintains two lists of CVE IDs that
may be of particular interest.
  
The **K**nown **E**xploited **V**ulnerabilities
list contains flaws that they've identified
being actively exploited by threat actors.

Fixing or mitigating vulnerabilities included
in the list should be highly prioritized
(great "signal-to-noise ratio").

![bg right:30%](images/08-namib_desert.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
The organisation ["FIRST"](https://www.first.org/) provides
the ["**E**xploit **P**rediction **S**coring **S**ystem"](https://www.first.org/epss/).  
  
Uses ~~machine learning and voodoo magic~~
sophisticated prediction models to guesstimate
how likely it is that a flaw will be
practically exploitable.  
  
Currently provided as API with scores
for all published CVEs. Use with caution.
  
(CISA has launched an alternative called
["**L**ikely **E**xploited **V**ulnerabilities"](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.41.pdf).)

![bg right:30%](images/08-brick_wall_metal_stairs.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Stig Nygaard (CC BY 2.0)" -->
We will cover the wide-spread
**C**ommon **V**ulnerability **S**coring **S**ystem
later during the course, don't worry...

![bg right:30%](images/08-stevnsfort.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Andreas Swane (CC BY 2.0)" -->
Manually monitoring CVEs is time-consuming.  

Tools like [OpenCVE](https://www.opencve.io) can help you
track/triage those relevant to your organisation.

![bg right:30%](images/08-abandoned_power_plant_control.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Guilhem Vellut (CC BY 2.0)" -->
Sounds amazing, doesn't it?
  
Spoiler alert: _it ain't all roses..._

![bg right:30%](images/08-koto_greenhouse_dome.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Matthias Ripp (CC BY 2.0)" -->
CNAs are responsible for allocating
CVE IDs and submitting description to MITRE.  
  
Product vendors are often their own CNA.  
  
They may be unresponsive to reports.
  
They could be incentivised to
procrastinate publication or polish
descriptions to downplay the severity.
  
The ["NotCVE" project](https://notcve.org/about.html) attempts to
provide an alternative. Will it succeed?

![bg right:30%](images/08-regensburg.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Franz van Duns (CC BY-SA 4.0)" -->
CVE IDs gets allocated and assigned
to bugs/behaviors that are not
security vulnerabilities.
  
Submitted by sloppy researches and
hallucinating AI bots.
  
Developers may dispute bogus claims,
but it's hard to get them removed
from the CVE database.  
  
A common work-around is to become
your own CNA to filter requests,
like [the curl project did](https://daniel.haxx.se/blog/2024/01/16/curl-is-a-cna/).

![bg right:30%](images/08-old_door_latch_and_lock.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Brocken Inaglory (CC BY-SA 3.0)" -->
Some software projects don't wanna spend
time on classifying whether a bug could
be a security vulnerability or not.

The Linux kernel team recently became
their own CNA and simply assigns a
CVE ID to each identified bug.
  
...thereby spamming the database
with a bunch of non-flaws.

![bg right:30%](images/08-yellowstone_falls.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
MITRE is mainly funded by the US government.

Like many similar organisations, there have
been significant uncertainty regarding
their ability to continue operating.

Furthermore, they've been failing to
maintain the database and promptly
allocate CVE IDs to CNAs.

Alternatives have appeared, like
[**EU**'s own **V**ulnerability **D**atabase](https://euvd.enisa.europa.eu/) and
the [decentralised **G**lobal **CVE** system](https://gcve.eu/).

![bg right:30%](images/08-rusty_shopping_basket_and_bike.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Marcin Wichary (CC BY 2.0)" -->
## Conclusions?

![bg right:30%](images/08-difference_engine.jpg)
