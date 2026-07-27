# 📖 Lab Overview

## Introduction

Imagine you're a SOC analyst starting your shift.

Instead of building the security platform, your job is to investigate the alerts that have already been detected.

Every day, organizations generate thousands of security events across endpoints, identities, email, cloud applications, and servers. Finding the alerts that actually matter—and responding to them quickly—is one of the biggest challenges for a Security Operations Center (SOC).

This is where **Microsoft Defender XDR** plays an important role.

Microsoft Defender XDR brings together security signals from multiple Microsoft security products into a single platform, allowing analysts to investigate incidents from one centralized location instead of switching between different security tools.

In this lab, I use Microsoft Defender XDR to investigate a security incident from start to finish. The project covers onboarding an endpoint, generating security telemetry, analyzing alerts, investigating the device timeline, performing threat hunting with Kusto Query Language (KQL), and documenting the investigation process.

Rather than focusing on building detection rules, this project focuses on the daily responsibilities of a SOC analyst after an incident has already been detected.

By the end of the lab, the complete investigation lifecycle is demonstrated—from endpoint onboarding and alert investigation to threat hunting, response, and Microsoft Sentinel integration.

---

# 🎯 Objectives

The primary objectives of this lab are to:

- Deploy and onboard a Windows endpoint into Microsoft Defender for Endpoint.
- Generate security telemetry for investigation.
- Investigate alerts and incidents within Microsoft Defender XDR.
- Analyze the Device Timeline and collected evidence.
- Perform threat hunting using Advanced Hunting (KQL).
- Understand how Defender XDR correlates alerts into incidents.
- Explore incident response capabilities available within Microsoft Defender.
- Integrate Microsoft Defender XDR with Microsoft Sentinel.
- Document the complete investigation workflow.

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Microsoft Defender XDR | Extended Detection and Response (XDR) platform |
| Microsoft Defender for Endpoint | Endpoint Detection and Response (EDR) |
| Microsoft Sentinel | SIEM Integration |
| Microsoft Azure | Cloud Platform |
| Windows 11 | Investigation Endpoint |
| Azure Virtual Machine | Lab Environment |
| Kusto Query Language (KQL) | Advanced Hunting |
| Microsoft Defender Portal | Incident Investigation |
| MITRE ATT&CK Framework | Threat Classification |

---

# 🧠 Skills Demonstrated

Throughout this project I demonstrate practical experience with:

- Microsoft Defender XDR
- Microsoft Defender for Endpoint
- Endpoint Investigation
- Incident Analysis
- Alert Triage
- Device Timeline Analysis
- Threat Hunting
- Advanced Hunting (KQL)
- MITRE ATT&CK Mapping
- Endpoint Telemetry Analysis
- Microsoft Sentinel Integration
- Security Incident Response
- SOC Investigation Workflow

---

# 🔄 Investigation Workflow

This lab follows the same workflow used by many Security Operations Centers:

```text
Endpoint

↓

Microsoft Defender for Endpoint

↓

Microsoft Defender XDR

↓

Alert Generated

↓

Incident Created

↓

Investigation

↓

Threat Hunting

↓

Response Actions

↓

Microsoft Sentinel
```

The following sections walk through each stage of this investigation step by step.
