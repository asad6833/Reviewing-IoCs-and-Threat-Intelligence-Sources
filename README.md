# Reviewing-IoCs-and-Threat-Intelligence-Sources


🧪 Assisted Lab: Reviewing IoCs and Threat Intelligence Sources
📘 Scenario

As a cybersecurity analyst at Structureality Inc., your role is to identify weaknesses, track vulnerabilities, and analyze malicious activity across the organization’s internal network. This lab focuses on understanding Indicators of Compromise (IoCs) and exploring open-source threat intelligence platforms used for threat hunting and defensive operations.

You will also evaluate security policy templates and explore CIS security benchmarks to understand how organizations build secure baselines and configuration standards.

All analysis is performed from the PC10 virtual machine running Windows Server 2019.

🖥️ Lab Environment

VM: PC10

OS: Windows Server 2019

Role: CySA+ Analyst Workstation

Network: Structureality server subnet

🎯 Learning Objectives
1.1 — System & Network Architecture Concepts

How network layout impacts threat visibility

Understanding attack surfaces and segmentation

1.4 — Threat Intelligence & Threat Hunting

Exploring IoCs

Using structured threat intelligence feeds

Reviewing malware campaigns (example: Mirai botnet)

1.5 — Efficiency & Process Improvement

Leveraging shared intelligence sources

Standardizing policies and baselines

2.5 — Vulnerability Response & Management

Reviewing exploits

Understanding CVEs

Prioritizing vulnerabilities using threat intel

🚀 Section 1 — Exploring IoC & Threat Intelligence Sources
🔹 1. CIS Real-Time Indicator Feeds

URL: https://www.cisecurity.org/ms-isac/services/real-time-indicator-feeds

CIS provides actionable indicators (malicious IPs, URLs, domains, hashes) to U.S. SLTT organizations. Review the feed overview to understand the type of intelligence provided.

🔹 2. AlienVault Open Threat Exchange (OTX)

URL: https://otx.alienvault.com/browse/global/pulses

Steps:

Search for mirai.

Open a Pulse (e.g., Mirai Botnet IOCs).

Review color-coded indicator types (FileHash, IPv4, URL, Domain, Hostname, etc.).

Select an indicator → view Analysis, Related Pulses, and metadata.

Test searches for:

domain

URL

IPv4

IPv6

hostname

hash

Correct Answer from Lab: One type of indicator is FileHash.

🚀 Section 2 — Exploring The Exploit Database (Exploit-DB)

URL: https://www.exploit-db.com/

Exploit-DB is a CVE-compliant archive of public exploits and vulnerable software widely used by penetration testers.

What You Reviewed:

Newest exploits in reverse chronological order

Exploit download links

Verification status

Exploit type (Local, Remote, DoS, WebApp)

Platform (Linux, Windows, PHP, Python, etc.)

Filters Explored:

Type

Platform

Author

Port

Tag

Correct Answer from Lab:
❌ Evil Twin / Rogue Access Point is not a valid Exploit-DB filter option.

Google Hacking Database (GHDB)

Navigate to GHDB

Filter by Files Containing Passwords

Open a Google dork

Review search results (without visiting any sites)

Additional sections explored:

Security Papers

Shellcodes

SearchSploit Manual

🚀 Section 3 — Evaluating SANS Security Policy Templates

URL: https://www.sans.org/information-security-policy/

SANS provides free, customizable security policy templates.

Network Security

Reviewed Wireless Communication Policy

Examined major sections:

Overview

Purpose

Scope

Policy

Policy Compliance

Related Standards

Definitions & Terms

Revision History

Application Security

Reviewed Web Application Security Policy (from ISO file)

Used LibreOffice Writer to:

Replace <Company Name> → CySA+ Lab Corp

Add a new Revision History entry:

Date: Today’s date

Responsible: SecManagement

Summary: Initial crafting and customization

Saved file as Web_App_Security_Policy_v1.1.doc

🚀 Section 4 — Accessing CIS Benchmarks & Configuration Guides

URL: https://www.cisecurity.org/cis-benchmarks/

CIS Benchmarks provide secure configuration guides for:

Operating Systems

Server Software

Cloud Providers

Mobile Devices

Network Devices

Desktop Software

Multi-Function Print Devices

Example Benchmarks Reviewed:

Microsoft Windows Server

Amazon Web Services (AWS)

Apple macOS

Firefox

Docker

Correct Answer:
❌ CIS does not have a benchmark for Discord.

🧾 Summary of Completion

✔ Explored multiple IoC repositories and threat intelligence feeds
✔ Analyzed Mirai botnet indicators
✔ Reviewed exploit sources and Google dorks
✔ Customized SANS security policy templates
✔ Navigated CIS benchmarks and configuration guides
✔ Strengthened skills in threat hunting, vulnerability analysis, and policy management
