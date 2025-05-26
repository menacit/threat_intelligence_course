---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
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
## CVE-2022-39945
```
An improper access control vulnerability [CWE-284] in FortiMail 7.2.0,
7.0.0 through 7.0.3, 6.4 all versions, 6.2 all versions, 6.0 all versions
may allow an authenticated admin user assigned to a specific domain to
access and modify other domains information via
insecure direct object references (IDOR).
```

---
## CVE-2022-44877
```
login/index.php in CWP (aka Control Web Panel or CentOS Web Panel) 7
before 0.9.8.1147 allows remote attackers to execute arbitrary
OS commands via shell metacharacters in the login parameter.
```

---
## CVE-2018-1000803
```
Gitea version prior to version 1.5.1 contains a CWE-200 vulnerability
that can result in Exposure of users private email addresses.
This attack appear to be exploitable via Watch a repository to receive
email notifications. Emails received contain the other recipients even
if they have the email set as private. This vulnerability appears to
have been fixed in 1.5.1.
```
