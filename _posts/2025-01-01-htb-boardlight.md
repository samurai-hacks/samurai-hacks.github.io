---
title: HTB - Boardlight
date: 2025-01-01 17:30:00 +/-0900
categories: [Hack The Box, Linux]
tags: [htb-boardlight, hackthebox, nmap, wfuzz, dolibarr, cve-2023-30253, ssh, mysql, linpeas, cve-2022-37706]     # TAG names should always be lowercase
---

## How I passed the OSCP+ in just four months without metasploit!

![OSCP+ Badge](/assets/img/oscp/oscp-2.png){: .center }
_OSCP+_

>Trust the process and keep trying harder...
{: .prompt-info }

Thank you for stopping by to read about my experience with the OSCP+ exam. Whether you're here as an aspiring penetration tester, a seasoned professional, or someone simply curious about what this journey entails, I’m thrilled to share my insights with you.

The OSCP+ exam is more than just a test; it’s a challenge that pushes you to your limits, builds your resilience, and deepens your understanding of cybersecurity concepts. In this post, I’ll walk you through the highs and lows, the lessons learned, and the resources that helped me navigate this rigorous assessment.

### OSCP+ Exam Structure

- 3 stand-alone machines (60 points in total)
  - 20 points per machine
    - 10 points for initial access
    - 10 points for privilege escalation

- 1 Active Directory (AD) set containing 3 machines (40 points in total)
  - Assumed Breach Scenario
    - 10 points for machine #1
    - 10 points for machine #2
    - 20 points for machine #3