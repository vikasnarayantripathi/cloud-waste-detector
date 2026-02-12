# Cloud Waste Detector

API-first cloud waste detection without cloud credentials.

Cloud Waste Detector analyzes public cloud usage signals and returns
**conservative, machine-readable insights** about potential cloud cost waste.

No dashboards. No automation. Just clear signals you can trust.

---

## API Endpoint

Base URL:
https://baselayer.world

All API requests are made relative to this base URL.

---

## What this API does

- Detects unused or underutilized cloud resources
- Estimates potential monthly cost waste (min–max ranges)
- Provides confidence-scored findings
- Requires **no access** to your cloud account

Built for developers, FinOps teams, audits, and infrastructure workflows.

---

## How it works (End-to-End)

1. **Generate a free API key**  
   Instantly generate a free API key using the `/key` endpoint.  
   No signup, no email, no UI.

2. **Run cloud waste scans**  
   Use the API key with `/scan` to receive structured insights about
   unused or over-provisioned cloud resources.

3. **Review cost-saving insights**  
   Each scan returns:
   - Estimated monthly waste (conservative range)
   - Confidence score
   - Machine-readable findings

4. **Upgrade when you hit limits**  
   Free usage is limited.  
   When limits are reached, upgrade your subscription and continue
   using the **same API key** without changing your integration.

This API is designed for **silent, infrastructure-style usage**.

---

## Quick Start

### Step 1: Generate a free API key
```bash
curl -X POST https://baselayer.world/key

### Step 1: Generate a free API key
```bash
curl -X POST https://baselayer.world/scan \
  -H "X-API-Key: YOUR_API_KEY"

How this API benefits you

Identify cloud cost waste without sharing credentials
Get realistic, conservative savings estimates
Integrate easily into scripts, CI pipelines, or audits
Avoid dashboards, alerts, and vendor lock-in
Use results programmatically (JSON-first)

API Reference
POST /key
Generate a free API key.
POST /scan
Run a cloud waste analysis.
GET /usage
Check current plan and usage.
Authentication is done via the X-API-Key header

Usage Limits & Pricing
Free plan: 5 scans total
Paid plan: 100 scans per month
Upgrading is handled via subscription and applies automatically
to your existing API key.

No re-integration required.
Philosophy
Cloud Waste Detector is insight-first, not action-first.
It tells you what looks wasteful and how confident the signal is —
you decide what to do next.
