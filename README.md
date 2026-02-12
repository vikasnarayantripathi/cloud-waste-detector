# Cloud Waste Detector

Detect hidden cloud cost waste without cloud credentials.

Cloud Waste Detector is an **API-first FinOps utility** that analyzes public cloud usage signals and returns **conservative, machine-readable insights** about unused or over-provisioned resources.

No dashboards. No automation. Just reliable data.

---

## What it does
- Identifies unused or underutilized cloud resources
- Estimates potential monthly cost waste (conservative ranges)
- Provides confidence-scored findings
- Requires **no access** to your cloud account

Designed for engineers, auditors, and FinOps teams who want signal—not UI.

---

## Try it

```bash
curl -X POST https://yourdomain.com/scan \
  -H "X-API-Key: YOUR_API_KEY"
