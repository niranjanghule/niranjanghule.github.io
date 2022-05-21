---
title: Common Vulnerabilities and Exposures Explained
date: 2022-05-21 19:26:00 +0530
categories: [Software Development, Security ]
tags: [cve]
toc: true
---

## What is CVE?

CVE, short for Common Vulnerabilities and Exposures, is a list of publicly disclosed computer security flaws. 
When someone refers to a CVE, they mean a security flaw that's been assigned a CVE ID number.

Security advisories issued by vendors and researchers almost always mention at least one CVE ID. 
CVEs help IT professionals coordinate their efforts to prioritize and address these vulnerabilities to make computer systems more secure.

## How does the CVE system work?
The CVE program is overseen by the MITRE corporation with funding from the Cybersecurity and Infrastructure Security Agency (CISA), part of the U.S. Department of Homeland Security.

CVE entries are brief. They don’t include technical data, or information about risks, impacts, and fixes. Those details appear in other databases, 
including the U.S. National Vulnerability Database (NVD), the CERT/CC Vulnerability Notes Database, and various lists maintained by vendors and other organizations.

Across these different systems, CVE IDs give users a reliable way to recognize unique vulnerabilities and coordinate the development of security tools and solutions.
The MITRE corporation maintains the CVE List, but a security flaw that becomes a CVE entry is often submitted by organizations and members of the open source community.

## About CVE identifiers
CVE identifiers are assigned by a CVE Numbering Authority (CNA). There are about 100 CNAs, representing major
 IT vendors—such as Red Hat, IBM, Cisco, Oracle, and Microsoft—as well as security companies and research organizations. MITRE can also issue CVEs directly.

CNAs are issued blocks of CVEs, which are held in reserve to attach to new issues as they are discovered. 

Thousands of CVE IDs are issued every year. A single complex product, such as an operating system, can accumulate hundreds of CVEs.

CVE reports can come from anywhere. A vendor, a researcher, or just an astute user can discover a flaw and bring it to someone’s attention. Many vendors offer bug bounties to encourage responsible disclosure of security issues. If you find a vulnerability in open source software you should submit it to the community.

One way or another, information about the flaw makes its way to a CNA. The CNA assigns the information a CVE ID, and writes a brief description and includes references. Then the new CVE is posted on the CVE website.

Often, a CVE ID is assigned before a security advisory is made public. It’s common for vendors to keep security flaws secret until a fix has been developed and tested. That reduces opportunities for attackers to exploit unpatched flaws.

Once made public, a CVE entry includes the CVE ID (in the format "CVE-2019-1234567"), a brief description of the security vulnerability or exposure, and references, which can include links to vulnerability reports and advisories.
