---
title: "Privacy Policy"
date: 2025-12-19
draft: false
layout: "page"
url: "/privacy"
description: "AegisPrime Privacy Policy - How we handle your data with security-first principles."
---

**Effective Date:** December 19, 2025  
**Version:** 1.0

---

## Our Commitment

AegisPrime is built by security professionals, for security professionals. We understand data sensitivity and have designed our platform with privacy as a core principle.

---

## Data We Collect

### What You Submit for Analysis
- Security alerts, logs, or event data you paste into the console
- **Processing:** Analyzed in-memory only
- **Storage:** Never stored persistently
- **Retention:** Discarded immediately after analysis

### Analysis Results
- Verdicts, risk scores, and recommendations generated
- **Storage:** Retained temporarily for your dashboard
- **Retention:** Cleared on session end or server restart

### Usage Data
- API request counts (per API key)
- Timestamps of requests
- Verdict distribution (aggregate, not content)
- **Purpose:** Service quality and rate limiting

### What We Do NOT Collect
- Personal identifiable information (PII) from your alerts
- Raw log content beyond your session
- IP addresses of your SOC endpoints
- Customer/client data from your alerts

---

## How We Use Data

| Purpose | Data Used |
|---------|-----------|
| Provide analysis | Alert text (in-memory only) |
| Display results | Analysis output (session-only) |
| Rate limiting | Request counts |
| Service improvement | Aggregate usage stats |

---

## Data Sharing

**We do NOT:**
- Sell your data to anyone
- Share data with advertisers
- Use your data to train public AI models
- Provide data to third parties

**We MAY:**
- Use third-party threat intelligence APIs (OTX, UrlScan) to enrich analysis
- These services only receive artifact hashes/values, not full alert context

---

## Data Security

- All traffic encrypted via HTTPS/TLS
- API keys hashed before storage (SHA-256)
- No persistent database of alert content
- Infrastructure hosted in US-based data centers (Railway/Cloudflare)

---

## Your Rights

You may:
- Request deletion of any stored data
- Revoke your API key at any time
- Request information about data we hold

Contact: **privacy@aegisprime.app**

---

## Children's Privacy

AegisPrime is a professional security tool not intended for users under 18.

---

## Changes to This Policy

We may update this policy. Material changes will be communicated via email to registered beta users.

---

## Contact

**AegisPrime**  
Email: privacy@aegisprime.app

---

*Last Updated: December 19, 2025*
