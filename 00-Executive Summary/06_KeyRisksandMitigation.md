#Key Risks and Mitigation
Effective risk management is critical to the organization’s overall cybersecurity posture. The following risks have been identified as high-priority due to their potential to impact operations, regulatory compliance, and brand reputation. Each risk is paired with current and planned mitigation strategies.

## 1. Inadequate Identity and Access Controls
- **Risk Description**: Excessive permissions, lack of multi-factor authentication (MFA), and delayed deprovisioning may allow unauthorized access to sensitive systems.
- **Business Impact**: Potential data breach, regulatory non-compliance, insider threat exposure.
- **Likelihood**: High
- **Impact Level**: High
- **Current Mitigation**:
  - Role-based access controls (RBAC) implemented
  - Ongoing MFA rollout
  - Quarterly access reviews
- **Planned Enhancements**:
  - Automate user deprovisioning via IAM tools
  - Implement Just-in-Time (JIT) access for admins

## Key Risks & Mitigation Strategies

| Risk Category        | Key Risk                           | Mitigation Strategy                       |
|----------------------|-------------------------------------|--------------------------------------------|
| Insider Threats      | Unauthorized access misuse         | Least privilege, DLP, monitoring            |
| Cloud Misconfig      | Public S3 buckets, open ports      | Cloud posture tools, IaC policies          |
| Phishing/Email       | Credential harvesting              | Phishing training, DMARC, MFA              |
| Vendor Dependencies  | Supply chain risk                  | Third-party risk management program        |

Risk management is an ongoing process. As new threats emerge and business needs evolve, this risk matrix will be continuously updated. The Information Security team conducts quarterly risk assessments and maintains open communication with key stakeholders to adapt swiftly and effectively.

Reviewed quarterly and integrated into enterprise risk register.
