# Organizational Risk Register

## Objective

This document presents the completed organizational risk register developed during the risk management process. It consolidates the identified risks, assessment results, ownership, and recommended treatment actions into a single management view.

The risk register was developed using the GRC Practice Lab and demonstrates a structured approach to enterprise risk management.

---

# Risk Register Summary

| Total Risks | Critical | High | Medium | Low |
|-------------|----------|------|--------|-----|
| 12 | 1 | 7 | 4 | 0 |

---

# Organizational Risk Register

| Risk | Category | Likelihood | Impact | Score | Priority | Owner | Recommended Treatment |
|------|----------|-----------:|-------:|-------:|----------|-------|-----------------------|
| Unauthorized access via compromised credentials | Access Control | 4 | 5 | 20 | Critical | IT Security | Enforce MFA and Conditional Access |
| Data breach through application vulnerability | Application Security | 3 | 5 | 15 | High | AppSec | Patch management and vulnerability scanning |
| Ransomware encrypting production databases | Application Security | 3 | 5 | 15 | High | SecOps | Immutable backups and EDR deployment |
| Extended outage from failed disaster recovery | Availability | 3 | 4 | 12 | High | Infrastructure | Disaster recovery testing |
| Vendor data breach affecting customers | Vendor Risk | 3 | 4 | 12 | High | Procurement | Vendor security assessments |
| API abuse causing service degradation | Availability | 4 | 3 | 12 | High | Platform Team | API gateway protection and monitoring |
| VPN compromise enabling lateral movement | Access Control | 3 | 4 | 12 | High | Network Team | MFA and network segmentation |
| Phishing attacks targeting employees | Human Error | 4 | 3 | 12 | High | IT Security | Security awareness training |
| PHI exposure via S3 misconfiguration | Data Protection | 2 | 5 | 10 | Medium | Cloud Team | Cloud security posture management |
| HIPAA non-compliance penalties | Compliance | 2 | 5 | 10 | Medium | Compliance | Policy reviews and compliance audits |
| Insider threat data exfiltration | Access Control | 2 | 4 | 8 | Medium | HR Security | DLP and privileged access monitoring |
| Supply chain attack via dependencies | Vendor Risk | 2 | 4 | 8 | Medium | Engineering | Software supply chain security controls |

---

# Risk Prioritization

The completed risk register demonstrates the organization's current risk profile:

- 1 Critical Risk
- 7 High Risks
- 4 Medium Risks
- 0 Low Risks

Immediate remediation efforts should focus on the Critical and High risks while Medium risks should be managed through scheduled treatment activities and continuous monitoring.

---

# Alignment with Risk Appetite

Each risk was evaluated against the organization's approved Risk Appetite Statement.

Risks exceeding approved tolerance levels require treatment and ongoing monitoring until residual risk falls within the organization's accepted appetite.

---

# Conclusion

The completed organizational risk register provides a centralized view of identified business and cybersecurity risks. It enables management to prioritize remediation efforts, assign accountability, monitor progress, and support informed risk-based decision making.
