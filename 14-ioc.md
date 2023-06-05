---
SPDX-FileCopyrightText: © 2023 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: IoCs"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Presentation about indicators of compromise in threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% M. Zamani, ESO (CC BY 2.0)" -->
## Indicators of Compromise
### Low-level threat sharing

![bg right:30%](images/14-observatory.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% M. Zamani, ESO (CC BY 2.0)" -->
Threat intelligence is not just for humans.  

Used to improve intrusion detection and prevention systems.

![bg right:30%](images/14-observatory.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Jonathan Torres (CC BY 4.0)" -->
## Like what exactly?
- IP addresses
- Domain names
- File hashes
- User agents / Client identifiers
- URL paths
- [JA3 / JA3S fingerprints](https://github.com/salesforce/ja3)
- Traffic patterns
- Bank account numbers

....

![bg right:30%](images/14-cyborg.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Jonathan Torres (CC BY 4.0)" -->
Converted into configuration for firewalls, EDR agents, log servers, HIDS, WAFs, etc.

![bg right:30%](images/14-cyborg.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Jonathan Torres (CC BY 4.0)" -->
### How do I get hold of these?

![bg right:30%](images/14-cyborg.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
### Feeds (Passive)
- [IPsum](https://github.com/stamparm/ipsum)
- [Proofpoint's Emerging Threats](https://rules.emergingthreats.net)
- [PhishTank](https://github.com/stamparm/ipsum)
- [SSLBL](https://sslbl.abuse.ch/)
- [disposable-email-domains](https://github.com/disposable-email-domains/disposable-email-domains)
- [Greynoise's blocklist](https://www.greynoise.io)

### APIs (Active)
- [VirusTotal](https://www.virustotal.com)
- [Focsec](https://focsec.com/)
 
![bg right:30%](images/14-chip_closeup.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Yellowcloud (CC BY 2.0)" -->
Not all sharing is done in the open.  

Information Sharing and
Analysis Centers (ISACs) exist to support specific private/public sectors and interest areas.
 
![bg right:30%](images/14-chip_closeup.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Miguel Discart (CC BY-SA 2.0)" -->
## What is MISP?
FOSS solution for threat sharing.  

Instances can subscribe and publish information to public or private communities.  

Normalize data from different feeds.

Provides a powerful search engine and
supports IoC import/export for common formats, such as STIX and YARA/Snort rules.
 
![bg right:30%](images/14-triangles.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Miguel Discart (CC BY-SA 2.0)" -->
### Let's have a look, shall we?
 
![bg right:30%](images/14-triangles.jpg)

