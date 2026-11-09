# Executive Summary — Northstar Office Supply

**Assessment type:** Simulated cybersecurity risk assessment  
**Organization:** Fictional 25-person online retailer  
**Assessment date:** November 2026  
**Prepared as:** Beginner GRC portfolio exercise

## Purpose

This exercise demonstrates a basic risk assessment process: identify important assets, describe credible threats, estimate risk, review example controls, and recommend treatment actions.

## Overall view

The fictional organization depends on cloud email, employee laptops, customer/order information, backups, and third-party services. The example register identifies several risks that could interrupt sales or expose business information. The highest priorities are account compromise, ransomware/business disruption, and weaknesses in endpoint maintenance.

## Priority observations

1. **Account compromise:** Phishing could lead to unauthorized access to employee email and connected business services. Prioritize multifactor authentication for all accounts, phishing reporting, and access reviews.
2. **Ransomware and recovery:** Backups may not be sufficient if restoration is not tested or backup copies are reachable from compromised systems. Test restores regularly and protect backup access.
3. **Endpoint vulnerabilities:** Inconsistent patch tracking may leave laptops exposed to known weaknesses. Establish patch deadlines, reporting, and exception approval.
4. **Excessive access:** Employees may retain access to customer/order data beyond their job requirements. Review permissions at onboarding, role changes, and termination.
5. **Third-party dependency:** A vendor outage or security incident could interrupt online sales. Document vendor contacts, review security commitments, and maintain a continuity procedure.

## Recommended near-term actions

| Priority | Action | Suggested owner |
|---|---|---|
| 1 | Enforce MFA on email and other critical services | IT Administrator |
| 2 | Test backup restoration and document results | IT Administrator |
| 3 | Create a monthly endpoint patch compliance report | IT Administrator |
| 4 | Review customer/order platform permissions | Business Operations Manager |
| 5 | Complete a basic review of critical vendors | Operations Manager |

## Management decisions

Management should confirm risk tolerance, approve owners and deadlines, and decide whether any residual risks will be accepted. Risk acceptance should be documented with the approver, rationale, and review date.

## Limitations

This report is based entirely on a fictional scenario and illustrative assumptions. It is not evidence that any real controls exist or work. It is not a formal audit, legal opinion, penetration test, or compliance certification.
