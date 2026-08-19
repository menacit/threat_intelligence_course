---
SPDX-FileCopyrightText: © 2026 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: CVSS basics exercise"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "Exercise in CVSS basics for threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Randy Adams (CC BY-SA 2.0)" -->
# Group exercise

![bg right:30%](images/10-abstract_pattern.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Randy Adams (CC BY-SA 2.0)" -->
### Exercise: CVSS base score
Participants are split into groups.  
  
Each group will be provided with five CVE IDs and
their descriptions. Based on the descriptions,
[calculate CVSS 4.0 base metrics](https://www.first.org/cvss/calculator/4-0).  

Guesstimation/basic research may be required.  
  
Send resulting CVSS vector strings to:
**[courses+ti_011001@%EMAIL_DOMAIN%](mailto:courses+ti_011001@%EMAIL_DOMAIN%)**

![bg right:30%](images/10-abstract_pattern.jpg)


---
## CVE-2017-6742
```
The Simple Network Management Protocol (SNMP) subsystem of Cisco IOS 12.0 through 12.4 and 15.0
through 15.6 and IOS XE 2.2 through 3.17 contains multiple vulnerabilities that could allow an
authenticated, remote attacker to remotely execute code on an affected system or cause an affected
system to reload. An attacker could exploit these vulnerabilities by sending a crafted SNMP packet
to an affected system via IPv4 or IPv6. Only traffic directed to an affected system can be used to
exploit these vulnerabilities. The vulnerabilities are due to a buffer overflow condition in the
SNMP subsystem of the affected software. The vulnerabilities affect all versions of SNMP: Versions
1, 2c, and 3. To exploit these vulnerabilities via SNMP Version 2c or earlier, the attacker must
know the SNMP read-only community string for the affected system. To exploit these vulnerabilities
via SNMP Version 3, the attacker must have user credentials for the affected system. All devices
that have enabled SNMP and have not explicitly excluded the affected MIBs or OIDs should be
considered vulnerable. Cisco Bug IDs: CSCve54313.
```

---
## CVE-2021-22009
```
The vCenter Server contains multiple denial-of-service vulnerabilities
in VAPI (vCenter API) service. A malicious actor with network access
to port 443 on vCenter Server may exploit these issues to create a
denial of service condition due to excessive memory consumption
by VAPI service.
```

---
## CVE-2026-20674
```
A privacy issue was addressed by removing sensitive data.
This issue is fixed in iOS 26.3 and iPadOS 26.3.
An attacker with physical access to a locked device may
be able to view sensitive user information.
```

---
## CVE-2022-44877
```
login/index.php in CWP (aka Control Web Panel or CentOS Web Panel) 7
before 0.9.8.1147 allows remote attackers to execute arbitrary
OS commands via shell metacharacters in the login parameter.
```

---
## CVE-2024-45200
```
In Nintendo Mario Kart 8 Deluxe before 3.0.3, the LAN/LDN local multiplayer
implementation allows a remote attacker to exploit a stack-based buffer overflow
upon deserialization of session information via a malformed browse-reply packet,
aka KartLANPwn. The victim is not required to join a game session with an attacker.
The victim must open the "Wireless Play" (or "LAN Play") menu from the game's
title screen, and an attacker nearby (LDN) or on the same LAN network as the victim
can send a crafted reply packet to the victim's console. This enables a remote attacker
to obtain complete denial-of-service on the game's process, or potentially,
remote code execution on the victim's console. The issue is caused by incorrect use of
the Nintendo Pia library.
```
