# Learn-SecByte-CTF-Labs-Collection-Linux-Privilege-Escalation-Morpheus-Matrix-Breakout
A curated collection of hands-on Linux privilege escalation CTF labs, covering automated and manual enumeration, SUID/SGID abuse, Linux capabilities, cron job exploitation, and credential hunting on Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on Linux security and privilege escalation labs designed to help cybersecurity students, CTF players, penetration testers, and security researchers master post-exploitation mechanics, system enumeration, and local privilege escalation vectors.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Elevating privileges on a compromised Linux host is a critical phase in modern penetration testing and red teaming. Hosted on [Learn SecByte](https://learn.secbyte.org/), the **Matrix Breakout 2: Morpheus** lab series provides realistic scenarios focused on post-foothold activities.

This collection guides you through essential local privilege escalation vectors, including manual system inspection, automated script execution, administrative misconfiguration analysis, Linux capabilities abuse, scheduled task (cron job) exploitation, and root access validation.

---

## Lab Collection & Index

Below is the complete, searchable index of all privilege escalation challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Matrix Breakout 2: Morpheus - Attack Path Analysis** | Threat Modeling | Attack surface mapping, entry point evaluation, path identification | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-attack-path-analysis) |
| 2 | **Matrix Breakout: Root Access Verification** | Flag & Access Validation | Root proof of compromise, flag validation, privilege audit | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-root-access-verification) |
| 3 | **Matrix Breakout 2: Capabilities in the Machine** | Privilege Escalation | Linux capabilities audit (`getcap`), binary exploitation | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-capabilities-in-the-machine) |
| 4 | **Morpheus SUID/SGID Abuse** | Privilege Escalation | SUID/SGID binary analysis, GTFOBins execution, path escalation | [Access Lab](https://learn.secbyte.org/ctf/morpheus-suid-sgid-abuse) |
| 5 | **Cron Job Privilege Escalation - Morpheus Breakout** | Privilege Escalation | Scheduled task inspection, wildcard injection, permission flaws | [Access Lab](https://learn.secbyte.org/ctf/cron-job-privilege-escalation-morpheus-breakout) |
| 6 | **Matrix Breakout 2: Morpheus - Misconfigured Services Exploitation** | Privilege Escalation | Local service exploitation, socket auditing, service misconfigurations | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-misconfigured-services-exploitati) |
| 7 | **Matrix Breakout 2: Morpheus - Linux Privilege Escalation Methodology** | Privilege Escalation | Structured local privilege escalation framework and workflow | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-linux-privilege-escalation-method) |
| 8 | **Matrix Breakout 2: Morpheus - Configuration File Analysis** | Post-Exploitation | Sensitive file permissions, readable config inspection, secret extraction | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-configuration-file-analysis) |
| 9 | **Matrix Breakout 2: Morpheus - Credential Discovery & Loot Hunting** | Post-Exploitation | Password harvesting, bash history review, SSH key discovery | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-credential-discovery-loot-hunting) |
| 10 | **Automated Linux Enumeration on Morpheus** | System Enumeration | Automated enumeration tooling (LinPEAS, LinEnum, LinPE), script analysis | [Access Lab](https://learn.secbyte.org/ctf/automated-linux-enumeration-on-morpheus) |
| 11 | **Manual Linux Enumeration on Morpheus** | System Enumeration | Command-line system auditing, environment inspection, process hunting | [Access Lab](https://learn.secbyte.org/ctf/manual-linux-enumeration-on-morpheus) |
| 12 | **Morpheus Linux Privilege Enumeration** | System Enumeration | User access rights, sudo permission review (`sudo -l`), group mapping | [Access Lab](https://learn.secbyte.org/ctf/morpheus-linux-privilege-enumeration) |

---

## Categories

### 1. Linux System Enumeration & Loot Hunting
Learn techniques for both manual and script-assisted local discovery to reveal hidden configuration secrets, credentials, and misconfigurations.
- [Manual Linux Enumeration on Morpheus](https://learn.secbyte.org/ctf/manual-linux-enumeration-on-morpheus)
- [Automated Linux Enumeration on Morpheus](https://learn.secbyte.org/ctf/automated-linux-enumeration-on-morpheus)
- [Morpheus Linux Privilege Enumeration](https://learn.secbyte.org/ctf/morpheus-linux-privilege-enumeration)
- [Matrix Breakout 2: Morpheus - Configuration File Analysis](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-configuration-file-analysis)
- [Matrix Breakout 2: Morpheus - Credential Discovery & Loot Hunting](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-credential-discovery-loot-hunting)

### 2. Local Privilege Escalation Vectors
Practice exploiting common Linux privilege escalation vectors to elevate from low-privileged users to root.
- [Matrix Breakout 2: Morpheus - Linux Privilege Escalation Methodology](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-linux-privilege-escalation-method)
- [Morpheus SUID/SGID Abuse](https://learn.secbyte.org/ctf/morpheus-suid-sgid-abuse)
- [Matrix Breakout 2: Capabilities in the Machine](https://learn.secbyte.org/ctf/matrix-breakout-2-capabilities-in-the-machine)
- [Cron Job Privilege Escalation - Morpheus Breakout](https://learn.secbyte.org/ctf/cron-job-privilege-escalation-morpheus-breakout)
- [Matrix Breakout 2: Morpheus - Misconfigured Services Exploitation](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-misconfigured-services-exploitati)

### 3. Attack Path Analysis & Root Verification
Analyze multi-stage exploit chains and establish verified root-level persistence and proof.
- [Matrix Breakout 2: Morpheus - Attack Path Analysis](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-attack-path-analysis)
- [Matrix Breakout: Root Access Verification](https://learn.secbyte.org/ctf/matrix-breakout-root-access-verification)

---

## Learning Path

Follow this progression path to develop systematic Linux privilege escalation capabilities:

1. **Phase 1: Initial System & User Enumeration** — Assess local system state and permissions:
   - [Manual Linux Enumeration on Morpheus](https://learn.secbyte.org/ctf/manual-linux-enumeration-on-morpheus)
   - [Morpheus Linux Privilege Enumeration](https://learn.secbyte.org/ctf/morpheus-linux-privilege-enumeration)
   - [Automated Linux Enumeration on Morpheus](https://learn.secbyte.org/ctf/automated-linux-enumeration-on-morpheus)

2. **Phase 2: Configuration & Credential Auditing** — Uncover stored secrets and sensitive files:
   - [Matrix Breakout 2: Morpheus - Configuration File Analysis](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-configuration-file-analysis)
   - [Matrix Breakout 2: Morpheus - Credential Discovery & Loot Hunting](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-credential-discovery-loot-hunting)

3. **Phase 3: Tactical Escalation Execution** — Exploit local vulnerabilities and misconfigurations:
   - [Matrix Breakout 2: Morpheus - Linux Privilege Escalation Methodology](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-linux-privilege-escalation-method)
   - [Morpheus SUID/SGID Abuse](https://learn.secbyte.org/ctf/morpheus-suid-sgid-abuse)
   - [Matrix Breakout 2: Capabilities in the Machine](https://learn.secbyte.org/ctf/matrix-breakout-2-capabilities-in-the-machine)
   - [Cron Job Privilege Escalation - Morpheus Breakout](https://learn.secbyte.org/ctf/cron-job-privilege-escalation-morpheus-breakout)
   - [Matrix Breakout 2: Morpheus - Misconfigured Services Exploitation](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-misconfigured-services-exploitati)

4. **Phase 4: Synthesis & Root Validation** — Map complete attack chains and verify root privileges:
   - [Matrix Breakout 2: Morpheus - Attack Path Analysis](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-attack-path-analysis)
   - [Matrix Breakout: Root Access Verification](https://learn.secbyte.org/ctf/matrix-breakout-root-access-verification)

---

## How to Use the Labs

1. Click on any challenge link from the index or category sections above.
2. Read the scenario details and requirements on [Learn SecByte](https://learn.secbyte.org/).
3. Connect to the target Linux instance via SSH or the terminal environment provided.
4. Perform local enumeration, identify system weaknesses, execute your privilege escalation vector, and retrieve the root flag.

---

## Disclaimer

This repository and its linked resources are strictly intended for educational, training, and authorized penetration testing research. Performing unauthorized security testing or exploitation on systems without prior written authorization is strictly prohibited and illegal.
