# 📊 Vendor Risk Scoring Matrix

## Purpose
Quantitative assessment framework for evaluating and monitoring vendor security and compliance risks with weighted criteria and actionable scoring guidance.

## Scoring Methodology

### Risk Categories & Weights
| Category | Weight | Rationale |
|----------|--------|-----------|
| **Data Security** | 30% | Highest impact on compliance and breach risk |
| **Compliance Posture** | 25% | Regulatory requirements and audit findings |
| **Business Continuity** | 20% | Service availability and disaster recovery |
| **Access Controls** | 15% | Identity management and privilege controls |
| **Vendor Stability** | 10% | Financial health and business longevity |

### Scoring Scale
- **1**: Excellent (minimal risk, industry best practices)
- **2**: Good (acceptable risk, standard practices)
- **3**: Fair (moderate risk, some concerns)
- **4**: Poor (high risk, significant gaps)
- **5**: Critical (unacceptable risk, immediate action required)

## Risk Assessment Criteria

### Data Security (Weight: 30%)

| Criteria | Score 1 | Score 2 | Score 3 | Score 4 | Score 5 |
|----------|---------|---------|---------|---------|---------|
| **Encryption** | AES-256 at rest + TLS 1.3 in transit | AES-256 at rest + TLS 1.2 | Some encryption gaps | Basic encryption only | No/weak encryption |
| **Data Classification** | Formal program with automated controls | Documented policies with manual controls | Basic classification | Ad-hoc approach | No classification |
| **Data Loss Prevention** | Advanced DLP with ML detection | Standard DLP tools deployed | Basic monitoring | Limited controls | No DLP |
| **Backup Security** | Encrypted, tested, immutable backups | Encrypted, regularly tested | Encrypted backups | Basic backups | No/poor backups |

### Compliance Posture (Weight: 25%)

| Criteria | Score 1 | Score 2 | Score 3 | Score 4 | Score 5 |
|----------|---------|---------|---------|---------|---------|
| **Certifications** | SOC2 Type II + ISO27001 + relevant regs | SOC2 Type II + one other | SOC2 Type I or equivalent | Basic certifications | No certifications |
| **Audit Results** | Clean audits, no findings | Minor findings, quick remediation | Some findings, remediation in progress | Multiple findings, slow remediation | Major findings, poor response |
| **Policy Framework** | Comprehensive, regularly updated | Good coverage, annual updates | Basic policies, irregular updates | Outdated policies | No formal policies |
| **Training Program** | Mandatory, tracked, role-based | Annual mandatory training | Basic security awareness | Ad-hoc training | No training program |

### Business Continuity (Weight: 20%)

| Criteria | Score 1 | Score 2 | Score 3 | Score 4 | Score 5 |
|----------|---------|---------|---------|---------|---------|
| **SLA Commitments** | >99.9% uptime with penalties | 99.5-99.9% uptime | 99-99.5% uptime | 95-99% uptime | <95% or no SLA |
| **Disaster Recovery** | Tested, <2hr RTO, <15min RPO | Tested, <4hr RTO, <1hr RPO | Basic DR plan, <24hr RTO | Documented but untested | No DR plan |
| **Incident Response** | 24/7 response, <1hr notification | Business hours, <4hr notification | <24hr response | Slow response | No formal IR |
| **Geographic Redundancy** | Multi-region active-active | Multi-region active-passive | Single region, multiple AZs | Single location | No redundancy |

### Access Controls (Weight: 15%)

| Criteria | Score 1 | Score 2 | Score 3 | Score 4 | Score 5 |
|----------|---------|---------|---------|---------|---------|
| **Authentication** | MFA mandatory, SSO integrated | MFA available, encouraged | MFA optional | Password-only with complexity | Weak/no requirements |
| **Authorization** | RBAC with least privilege | RBAC implemented | Basic role separation | Shared accounts common | No access controls |
| **Account Management** | Automated provisioning/deprovisioning | Manual but documented | Irregular review process | Poor account hygiene | No management |
| **Privileged Access** | PAM solution, session recording | Dedicated admin accounts | Separate admin processes | Elevated standard accounts | No privilege separation |

### Vendor Stability (Weight: 10%)

| Criteria | Score 1 | Score 2 | Score 3 | Score 4 | Score 5 |
|----------|---------|---------|---------|---------|---------|
| **Financial Health** | Strong financials, profitable | Stable revenue, minor losses | Break-even or small losses | Declining revenue | Financial distress |
| **Market Position** | Market leader, strong brand | Established player | Growing market share | Niche or declining | Struggling/unknown |
| **Customer Base** | Large, diverse, enterprise | Medium, mixed segments | Small but growing | Limited customer base | Few customers |
| **Management Team** | Experienced, stable leadership | Good track record | Some turnover | High turnover | Inexperienced team |

## Vendor Assessment Scorecard

### Vendor: [Vendor Name]
**Assessment Date**: ___________  
**Assessor**: _______________  
**Next Review**: ___________

| Category | Raw Score | Weight | Weighted Score | Notes |
|----------|-----------|--------|----------------|--------|
| Data Security | ___/5 | 30% | ___/1.5 | |
| Compliance Posture | ___/5 | 25% | ___/1.25 | |
| Business Continuity | ___/5 | 20% | ___/1.0 | |
| Access Controls | ___/5 | 15% | ___/0.75 | |
| Vendor Stability | ___/5 | 10% | ___/0.5 | |
| **Total Weighted Score** | | | **___/5.0** | |

### Risk Level Classification
- **1.0-1.5**: Low Risk (Proceed with standard terms)
- **1.6-2.5**: Medium Risk (Proceed with additional controls)
- **2.6-3.5**: High Risk (Extensive due diligence required)
- **3.6-4.5**: Very High Risk (Consider alternatives)
- **4.6-5.0**: Critical Risk (Do not engage)

## Vendor Portfolio Overview

| Vendor Name | Service Type | Risk Score | Risk Level | Contract Value | Last Review | Next Review |
|-------------|--------------|------------|------------|---------------|-------------|-------------|
| Acme Health Analytics | Data analytics | 2.1 | Medium | $50K/year | 01/15/2025 | 07/15/2025 |
| CloudSync Storage | Backup/storage | 1.8 | Medium | $25K/year | 03/20/2025 | 09/20/2025 |
| SecurePay Processing | Payment processing | 1.4 | Low | $120K/year | 02/10/2025 | 02/10/2026 |
| BasicTools CRM | Customer management | 3.2 | High | $30K/year | 04/05/2025 | 07/05/2025 |

## Risk Mitigation Requirements

### Medium Risk (2.1-3.0)
- [ ] Enhanced contract terms with security requirements
- [ ] Quarterly security posture reviews
- [ ] Business Associate Agreement (if applicable)
- [ ] Regular penetration testing reports
- [ ] Incident notification requirements

### High Risk (3.1-4.0)
- [ ] On-site security assessment
- [ ] Escrow arrangements for critical services
- [ ] Alternative vendor identification
- [ ] Enhanced monitoring and audit rights
- [ ] Shorter contract terms with frequent reviews

### Very High Risk (4.1-5.0)
- [ ] Executive approval required
- [ ] Comprehensive remediation plan
- [ ] Continuous monitoring
- [ ] Exit strategy planning
- [ ] Alternative vendor procurement

## Continuous Monitoring

### Automated Alerts
- [ ] Security incident notifications
- [ ] SLA breach alerts
- [ ] Certification expiration warnings
- [ ] Financial health changes
- [ ] Regulatory enforcement actions

### Periodic Reviews
| Review Type | Frequency | Trigger Conditions |
|-------------|-----------|-------------------|
| **Light Review** | Quarterly | Standard monitoring |
| **Full Assessment** | Annually | Contract renewal |
| **Emergency Review** | As needed | Security incidents, breaches |
| **Market Assessment** | Bi-annually | New alternatives, pricing changes |

## Vendor Communication Templates

### Risk Score Communication (Internal)
```
VENDOR RISK ASSESSMENT - [Vendor Name]

Risk Score: X.X/5.0 ([Risk Level])
Previous Score: X.X (Change: +/- X.X)

Key Changes:
- [Improvement/degradation area]
- [Action taken/required]

Recommendation: [Continue/enhance controls/consider alternatives]
```

### Vendor Improvement Request
```
Dear [Vendor Name],

During our recent security assessment, we identified opportunities to strengthen our partnership through improved security posture:

Priority Items:
1. [Specific requirement with timeline]
2. [Specific requirement with timeline]

We value our partnership and look forward to working together on these enhancements. Please provide an implementation timeline by [date].
```

## Action Items

| Vendor | Issue | Priority | Owner | Due Date | Status |
|--------|-------|----------|-------|----------|--------|
| BasicTools CRM | SOC2 certification expired | High | Procurement | MM/DD/YYYY | ⬜ |
| Acme Health | Backup testing documentation | Medium | IT | MM/DD/YYYY | ⬜ |

## Review and Approval

**Assessment Period**: ___________
**Completed By**: _______________
**Reviewed By**: _______________
**Approved By**: _______________ **Date**: ___________
