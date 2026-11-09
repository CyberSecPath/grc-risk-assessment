# Small Business GRC Risk Assessment

A beginner-friendly, fictional Governance, Risk, and Compliance (GRC) portfolio project. It demonstrates how to identify information assets, document cybersecurity risks, evaluate existing controls, prioritize remediation, and communicate risk to management.

> **Portfolio disclaimer:** This is a simulated assessment for a fictional company. No real organization, systems, vulnerabilities, or confidential information were assessed. The ratings are illustrative and are not a formal audit or compliance attestation.

## Scenario

**Northstar Office Supply** is a fictional 25-person company that sells office supplies online and operates a small office. It uses cloud email, a customer/order platform, employee laptops, and a third-party payment processor. The company has a small IT team and limited security resources.

## Project objectives

- Identify important business information assets.
- Record realistic cybersecurity risks and their business impact.
- Rate inherent risk before considering controls.
- Document existing controls and estimate residual risk.
- Recommend practical risk treatment actions with owners and target dates.
- Present a concise management summary.

## Repository contents

| Path | Purpose |
|---|---|
| `data/asset_inventory.csv` | Example asset inventory |
| `data/risk_register.csv` | Example risk register with scoring |
| `data/control_assessment.csv` | Example control review |
| `data/risk_treatment_plan.csv` | Example remediation plan |
| `templates/asset_inventory_template.csv` | Blank asset inventory |
| `templates/risk_register_template.csv` | Blank risk register |
| `templates/control_assessment_template.csv` | Blank control review |
| `templates/risk_treatment_plan_template.csv` | Blank treatment plan |
| `reports/executive_summary.md` | Management-facing summary |
| `methodology/risk_methodology.md` | Rating scales and assessment approach |

## How to use the CSV files

Open the CSV files in Excel, Google Sheets, or another spreadsheet application. The `data/` folder contains completed fictional examples. The `templates/` folder contains blank versions you can reuse.

### Risk scoring

This project uses a simple 1–5 scale:

- **Likelihood:** 1 = Rare, 2 = Unlikely, 3 = Possible, 4 = Likely, 5 = Almost certain.
- **Impact:** 1 = Insignificant, 2 = Minor, 3 = Moderate, 4 = Major, 5 = Severe.
- **Risk score:** Likelihood × Impact.
- **Priority bands:** 1–4 Low; 5–9 Moderate; 10–16 High; 17–25 Critical.

Inherent risk is the score before considering controls. Residual risk is the estimated remaining risk after considering the listed controls. These ratings are judgment-based examples, not measured probabilities.

## Key findings in this simulated assessment

1. Phishing and account compromise could expose company email and business information.
2. Inconsistent laptop patching could leave endpoints exposed to known vulnerabilities.
3. A ransomware incident could disrupt operations if backups are not tested and isolated.
4. Excessive access to customer/order information could increase the impact of an account compromise.
5. Vendor or payment-platform disruption could affect online sales.

The project recommends practical improvements such as multifactor authentication, recurring access reviews, centralized patch tracking, backup restoration tests, and vendor security reviews.

## Suggested workflow

1. Read `methodology/risk_methodology.md`.
2. Review the asset inventory.
3. Review each risk and its inherent/residual score.
4. Compare the control assessment with the risk register.
5. Review the treatment plan and identify the highest-priority actions.
6. Read the executive summary and explain the top risks in your own words.

## Skills demonstrated

- GRC documentation and risk identification
- Asset inventory and data classification
- Likelihood/impact risk analysis
- Control assessment
- Risk treatment and remediation tracking
- Management reporting
- Spreadsheet-based documentation

## Important limitations

This is an educational demonstration, not legal advice, a penetration test, a security audit, or a certification against NIST, ISO 27001, PCI DSS, or any other framework. The fictional controls and ratings should not be represented as verified facts about a real company.
