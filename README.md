# 📖 Overview

## Introduction

Imagine you're a SOC analyst investigating a newly detected security incident.

Your job isn't to build the security platform—it's to understand what happened, determine whether the activity is malicious, assess its impact, and decide on the appropriate response.

Modern organizations generate millions of endpoint events every day, making it impossible to investigate every event manually. Instead, security analysts rely on Endpoint Detection and Response (EDR) platforms such as **Microsoft Defender for Endpoint** to collect telemetry, detect suspicious behaviour, correlate related events into incidents, and provide the tools needed to investigate and respond efficiently.

In this lab, I deployed a Windows endpoint in Microsoft Azure and onboarded it into Microsoft Defender for Endpoint. Once connected, the endpoint continuously generated security telemetry, allowing me to investigate alerts, analyze endpoint activity, perform threat hunting using Kusto Query Language (KQL), and execute basic response actions from within the Defender portal.

Rather than focusing on detection engineering, this project demonstrates the day-to-day responsibilities of a Security Operations Center (SOC) analyst after an endpoint has been onboarded into Microsoft Defender for Endpoint.

By the end of this lab, the complete investigation workflow is demonstrated—from endpoint onboarding and exposure assessment to incident investigation, threat hunting, and response.

---

# 🎯 Objectives

The objectives of this lab are to:

- Deploy a Windows endpoint in Microsoft Azure.
- Onboard the endpoint into Microsoft Defender for Endpoint.
- Explore Device Inventory and Exposure information.
- Review Threat & Vulnerability Management recommendations.
- Generate endpoint security telemetry.
- Investigate alerts and incidents.
- Perform threat hunting using Advanced Hunting (KQL).
- Execute basic endpoint response actions.
- Document the investigation process from start to finish.

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Microsoft Defender for Endpoint | Endpoint Detection & Response (EDR) |
| Microsoft Azure | Cloud Platform |
| Windows 11 | Endpoint Device |
| Azure Virtual Machine | Investigation Environment |
| Kusto Query Language (KQL) | Advanced Hunting |
| Microsoft Defender Portal | Security Investigation |
| MITRE ATT&CK Framework | Threat Classification |

---

# 🎯 Skills Demonstrated

This lab demonstrates practical experience with:

- Microsoft Defender for Endpoint
- Endpoint Detection & Response (EDR)
- Device Onboarding
- Device Inventory
- Threat & Vulnerability Management
- Security Incident Investigation
- Alert Analysis
- Device Timeline Analysis
- Process Tree Investigation
- Threat Hunting
- Advanced Hunting (KQL)
- Endpoint Response
- MITRE ATT&CK Mapping
- SOC Investigation Workflow

---

# 🔄 Investigation Workflow

This project follows a typical endpoint investigation workflow used by Security Operations Centers.

```text
Windows Endpoint
        │
        ▼
Microsoft Defender for Endpoint
        │
        ▼
Device Inventory & Exposure
        │
        ▼
Threat & Vulnerability Assessment
        │
        ▼
Endpoint Security Events
        │
        ▼
Alert & Incident Investigation
        │
        ▼
Advanced Hunting (KQL)
        │
        ▼
Response Actions
        │
        ▼
Investigation Report
```

The following sections document each phase of the investigation in detail.
