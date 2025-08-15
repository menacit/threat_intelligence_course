---
SPDX-FileCopyrightText: © 2025 Menacit AB <foss@menacit.se>
SPDX-License-Identifier: CC-BY-SA-4.0

title: "Threat intelligence course: More example observations"
author: "Joel Rangsmo <joel@menacit.se>"
footer: "© Course authors (CC BY-SA 4.0)"
description: "More example observations for threat intelligence course"
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
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
# Example observations
### A few more for y'all!

![bg right:30%](images/27-orange_lens_on_rock.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
Let's take a look at some more security
related happenings and use what we've
learned to analyze them.

![bg right:30%](images/27-orange_lens_on_rock.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
- New ransomware recovery technique
- Concerns about chip backdoors
- Post-patch abuse of edge devices
- Security tool "Newtowner" released
- Sentencing of laptop farmer
- Conclusion of "AI cyber challenge"
- Flaws in backup software
- Criticism of "digital escorts" program
- Incident response by National Guard
- EU's "internal security strategy"

![bg right:30%](images/27-orange_lens_on_rock.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Dennis van Zuijlekom (CC BY-SA 2.0)" -->
### [New ransomware recovery technique](https://securityaffairs.com/181064/malware/researchers-cracked-the-encryption-used-by-darkbit-ransomware.html)
- Israeli security company Profero has developed a method to recover files encrypted by the "DarkBit" ransomware
- Exploits weakness in custom RNG for AES key
- Debate regarding attribution
- Similar techniques have previously been published for other ransomware variants

![bg right:30%](images/27-lock_insides.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Dennis van Zuijlekom (CC BY-SA 2.0)" -->
### Lessons / Takeaways
- Don't roll your own crypto!
- May be worth keeping encrypted data around if you can afford it
- Hard to keep geopolitical motives separate from cybersecurity

![bg right:30%](images/27-lock_insides.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% FMN Lab (CC BY 4.0)" -->
### [Concerns about chip backdoors](https://asiatimes.com/2025/08/china-fears-nvidia-chips-could-track-trace-and-shut-down-its-ais/)
- Chinese government agency questions Nvidia about potential chip backdoors
- Concerns of spying/disruption risks
- Points at the US "Chip Security Act"
- Historically similar fears have been brought up regarding Chinese technology products

![bg right:30%](images/27-electro_optical_modulator.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% FMN Lab (CC BY 4.0)" -->
### Lessons / Takeaways
- Supply chain security starts at the silicon
- Can't escape geopolitics!
- Work on verifiable HW/SW, such as the ["Betrusted Initative"](https://betrusted.io/)

![bg right:30%](images/27-electro_optical_modulator.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% CGP Grey (CC BY 2.0)" -->
### [Post-patch abuse of edge devices](https://www.cybersecuritydive.com/news/sonicwall-says-recent-attack-wave-involved-previously-disclosed-flaw-not-z/757067/)
- Firewalls from the vendor SonicWall have been implicated in several ransomware attacks
- Affected systems were fully patched
- Zero day first suspected, but investigation show abuse of credentials stolen during usage of earlier vulnerable version

![bg right:30%](images/27-bletchley_park_computer_wiring.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% CGP Grey (CC BY 2.0)" -->
### Lessons / Takeaways
- Once again: security products ain't necessarily secure products
- Simply applying patches may not be enough. Check routines and procedures
- At what point do you throw out a vendor/solution from your environment?

![bg right:30%](images/27-bletchley_park_computer_wiring.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Sergei F (CC BY 2.0)" -->
### [Security tool "Newtowner" released](https://github.com/assetnote/newtowner)
- ASM provider Assetnote has published a software utility called "Newtowner" on GitHub
- Performs HTTP requests from CI/CD and cloud services against a target URL
- Aids security testing by exposing lax configuration of firewalls/ACLs/etc.

![bg right:30%](images/27-retro_switchboard_sepia.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Sergei F (CC BY 2.0)" -->
### Lessons / Takeaways
- Nothing revolutionary, but neat package
- Exploits very common misconfiguration
- Restrictions based on IP addresses work badly in the cloud world, but may still minimize attack surface

![bg right:30%](images/27-retro_switchboard_sepia.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Halfrain (CC BY-SA 2.0)" -->
### [Sentencing of laptop farmer](https://therecord.media/arizona-woman-sentenced-north-korean-laptop-farm)
- US courts sentence woman to prison for running a "laptop farm" at her home
- Utilised by North Korean spies/hackers to work for 309 different companies using 68 stolen identities and 90 laptops
- Employment provided money and highly-privileged access

![bg right:30%](images/27-red_moon.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Halfrain (CC BY-SA 2.0)" -->
### Lessons / Takeaways
- Background checks and onboarding process
- Is it your employee actually working?
- The risks of malicious insiders are expensive to mitigate, especially IT roles

![bg right:30%](images/27-red_moon.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
### [Conclusion of "AI cyber challenge"](https://www.darpa.mil/news/2025/aixcc-results)
- DARPA competition for automated identification and patching of vulnerabilities
- Injection of 70 "synthetic flaws" in software into 54 million **L**ines **o**f **C**ode
- 54 identified, 43 patched
- Found 18 real/unrelated flaws
- 91% accuracy for winning team
- Combination of LLMs and "traditional tools"
- Open sourcing of contestant solutions, like [Trail of Bits' "Buttercup"](https://blog.trailofbits.com/2025/08/08/buttercup-is-now-open-source/)

![bg right:30%](images/27-dome_with_pink_flower_bushes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
### Lessons / Takeaways
- That is quite cool!
- Provably useful, not just marketing
- Subsidise make real costs tricky to determine
- Only 18 real/unrelated flaws?!

![bg right:30%](images/27-dome_with_pink_flower_bushes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
### [Flaws in backup software](https://www.veeam.com/kb4743)
- Software vendor Veeam discloses several vulnerabilities in their backup solution
- The most severe (CVSS v3.0 9.9) enable attackers with low-privileged domain accounts to gain **R**emote **C**ode **E**xecution
- Flaw expected to become popular in ransomware attacks

![bg right:30%](images/27-strapped_pipes_and_bushes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
### Lessons / Takeaways
- As noted by the ["best-practices"](https://bp.veeam.com/security/Design-and-implementation/Hardening/Workgroup_or_Domain.html#best-practice), segment backup and production environment
- Documentation may provide cheap wins
- Consider offline storage and possibly<br>**W**rite **O**nce **R**ead **M**any media
- How do you detect compromised backups?

![bg right:30%](images/27-strapped_pipes_and_bushes.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Q8682 (CC BY-SA 4.0)" -->
### [Criticism of "digital escorts" program](https://www.propublica.org/article/microsoft-digital-escorts-pentagon-defense-department-china-hackers)
- Reporting from ProPublica reveals questionable security practices by Microsoft when managing cloud infrastructure for US defense department
- Technical personnel in China maintained the environment under supervision of US citizens with security clearance
- "Digital escorts" were badly paid and often lacked technical skills
- Promise to adjust practices after governmental pressure

![bg right:30%](images/27-hebel_barbwire_art.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Q8682 (CC BY-SA 4.0)" -->
### Lessons / Takeaways
- OMGWTFBBQ?!
- Similar approaches in high-security systems
- Defending against malicious technical personnel is extremely difficult
- ~~Trust, but~~ verify! 

![bg right:30%](images/27-hebel_barbwire_art.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Nick Watts (CC BY-SA 2.0)" -->
### [Incident response by National Guard](https://therecord.media/minnesota-governor-activates-national-guard-st-paul-cyber-attack)
- City in Minnesota shutdown their IT environment to disrupt ongoing intrusion 
- State governor request help from the National Guard's "cyber forces"
- Work together with local personnel during **I**ncident **R**esponse and recovery

![bg right:30%](images/27-dome_bridge.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Nick Watts (CC BY-SA 2.0)" -->
### Lessons / Takeaways
- Large-scale IR has mostly been handled by commercial actors 
- Capacity to handle "cyberwar"?
- Mayhaps something for Sweden to consider

![bg right:30%](images/27-dome_bridge.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Cory Doctorow (CC BY-SA 2.0)" -->
### [EU's "internal security strategy"](https://ec.europa.eu/commission/presscorner/detail/en/ip_25_1599)
- European Commission presents 5 year roadmap called "ProtectEU" to strengthen law enforcement's capabilities to access data
- Stricter data retention requirements
- Tools to combat E2EE communication and anonymization services like VPNs
- Experts highlight security/privacy risks

![bg right:30%](images/27-chip_city.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Cory Doctorow (CC BY-SA 2.0)" -->
### Lessons / Takeaways
- The quest to find a balance between privacy and security continues
- Not only a "rebranding of Chat Control"
- Commission _VS_ Parliament
- Will service operators comply?

![bg right:30%](images/27-chip_city.jpg)

---
<!-- _footer: "%ATTRIBUTION_PREFIX% Joel Rangsmo (CC BY-SA 4.0)" -->
## Wrapping up
Any other thoughts or takeaways
that you wanna bring up?

![bg right:30%](images/27-orange_lens_on_rock.jpg)
