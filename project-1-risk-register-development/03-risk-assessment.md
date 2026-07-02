# Risk Assessment

## Objective

The objective of this phase is to evaluate each identified organizational risk by analyzing its likelihood of occurrence and potential business impact. The assessment enables management to prioritize risks based on their overall risk exposure and determine which risks require immediate treatment.

---

# Risk Assessment Methodology

Each identified risk was evaluated using a qualitative risk assessment model based on:

- **Likelihood (L):** The probability that the risk event will occur.
- **Impact (I):** The potential business impact if the risk materializes.
- **Inherent Risk Score:** Calculated as:

> **Risk Score = Likelihood × Impact**

The resulting score was used to classify risks into Critical, High, Medium, or Low priority.

---

# Risk Assessment Results

| Risk | Category | Likelihood | Impact | Risk Score | Risk Level |
|------|----------|-----------:|--------:|-----------:|------------|
| Unauthorized access via compromised credentials | Access Control | 4 | 5 | 20 | Critical |
| Data breach through application vulnerability | Application Security | 3 | 5 | 15 | High |
| Ransomware encrypting production databases | Application Security | 3 | 5 | 15 | High |
| Extended outage from failed disaster recovery | Availability | 3 | 4 | 12 | High |
| Vendor data breach affecting customers | Vendor Risk | 3 | 4 | 12 | High |
| API abuse causing service degradation | Availability | 4 | 3 | 12 | High |
| VPN compromise enabling lateral movement | Access Control | 3 | 4 | 12 | High |
| Phishing attacks targeting employees | Human Error | 4 | 3 | 12 | High |
| PHI exposure via S3 misconfiguration | Data Protection | 2 | 5 | 10 | Medium |
| HIPAA non-compliance penalties | Compliance | 2 | 5 | 10 | Medium |
| Insider threat data exfiltration | Access Control | 2 | 4 | 8 | Medium |
| Supply chain attack via dependencies | Vendor Risk | 2 | 4 | 8 | Medium |

---

# Risk Assessment Summary

The assessment identified:

| Risk Level | Number of Risks |
|------------|----------------:|
| Critical | 1 |
| High | 7 |
| Medium | 4 |
| Low | 0 |

The highest-priority risk is **Unauthorized access via compromised credentials**, with an inherent risk score of **20**.

The remaining High risks primarily involve application security, availability, vendor risk, and human factors, while the Medium risks require monitoring and planned mitigation activities.

---

# Key Observations

- Identity and Access Management represents the organization's highest-risk area.
- Application Security risks account for multiple high-priority findings.
- Vendor Risk remains a significant concern because of third-party dependencies.
- Human error continues to contribute significantly to cybersecurity exposure.
- Compliance-related risks remain important despite lower likelihood because of their potentially severe regulatory impact.

---

# Skills Demonstrated

- Risk Assessment
- Likelihood Analysis
- Business Impact Analysis
- Risk Scoring
- Risk Prioritization
- Inherent Risk Evaluation
- Governance, Risk, and Compliance (GRC)
