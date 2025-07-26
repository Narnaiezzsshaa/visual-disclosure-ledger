# 🔐 Vendor Security Questionnaire

## Purpose
Comprehensive security assessment framework for evaluating vendor security posture before onboarding and during ongoing relationship management.

## Instructions for Vendors
- Complete all applicable sections honestly and thoroughly
- Provide supporting documentation where requested
- Mark any questions as "Not Applicable" with brief explanation
- Submit responses within [X business days]
- Questions? Contact: [procurement@company.com]

## Instructions for Internal Teams
- Customize questions based on vendor risk level and data sensitivity
- Weight responses according to your risk tolerance
- Follow up on concerning responses before making procurement decisions
- Store completed questionnaires in vendor management system

---

## Vendor Information

| Field | Response |
|-------|----------|
| **Company Name** | |
| **Primary Contact** | |
| **Contact Email** | |
| **Contact Phone** | |
| **Service/Product Description** | |
| **Data Types Handled** | ☐ PII ☐ PHI ☐ Financial ☐ Proprietary ☐ None |
| **Proposed Contract Value** | |
| **Proposed Contract Term** | |
| **Primary Business Location** | |
| **Data Processing Locations** | |

---

## Section 1: Corporate & Governance

### 1.1 Company Information
| Question | Response | Comments |
|----------|----------|----------|
| How long has your company been in business? | | |
| How many employees does your company have? | | |
| What is your annual revenue range? | ☐ <$1M ☐ $1-10M ☐ $10-100M ☐ >$100M | |
| Are you publicly traded? | ☐ Yes ☐ No | |
| Do you have cyber liability insurance? | ☐ Yes ☐ No | If yes, coverage amount: |

### 1.2 Information Security Governance
| Question | Response | Supporting Evidence |
|----------|----------|-------------------|
| Do you have a designated Chief Information Security Officer (CISO) or equivalent? | ☐ Yes ☐ No | |
| Do you have formal information security policies? | ☐ Yes ☐ No | Policy index or table of contents |
| When were your security policies last reviewed/updated? | | |
| Do you provide annual security training to all employees? | ☐ Yes ☐ No | Training completion rates |
| Do you have an information security steering committee? | ☐ Yes ☐ No | Committee charter |

---

## Section 2: Compliance & Certifications

### 2.1 Industry Certifications
| Certification | Status | Expiration Date | Audit Firm | 
|---------------|--------|----------------|------------|
| **SOC 2 Type I** | ☐ Current ☐ In Progress ☐ Not Applicable | | |
| **SOC 2 Type II** | ☐ Current ☐ In Progress ☐ Not Applicable | | |
| **ISO 27001** | ☐ Current ☐ In Progress ☐ Not Applicable | | |
| **FedRAMP** | ☐ Current ☐ In Progress ☐ Not Applicable | | |
| **PCI DSS** | ☐ Current ☐ In Progress ☐ Not Applicable | | |
| **HIPAA** | ☐ Compliant ☐ Not Applicable | | |

**Required**: Please provide copies of current certificates and most recent audit reports.

### 2.2 Regulatory Compliance
| Regulation | Applicable | Compliance Status | Last Assessment |
|------------|------------|------------------|-----------------|
| **GDPR** (EU data) | ☐ Yes ☐ No | ☐ Compliant ☐ In Progress | |
| **CCPA** (California) | ☐ Yes ☐ No | ☐ Compliant ☐ In Progress | |
| **HIPAA** (Healthcare) | ☐ Yes ☐ No | ☐ Compliant ☐ In Progress | |
| **SOX** (Financial reporting) | ☐ Yes ☐ No | ☐ Compliant ☐ In Progress | |
| **Industry-specific regulations** | ☐ Yes ☐ No | ☐ Compliant ☐ In Progress | Specify: |

---

## Section 3: Data Security & Privacy

### 3.1 Data Protection
| Question | Response | Details |
|----------|----------|---------|
| What types of encryption do you use for data at rest? | ☐ AES-256 ☐ AES-128 ☐ Other ☐ None | Specify other: |
| What encryption do you use for data in transit? | ☐ TLS 1.3 ☐ TLS 1.2 ☐ Other ☐ None | Specify other: |
| How do you manage encryption keys? | ☐ HSM ☐ Cloud KMS ☐ Internal ☐ Third-party | Service provider: |
| Do you have a data classification program? | ☐ Yes ☐ No | Classification levels: |
| How often do you rotate encryption keys? | | |

### 3.2 Data Handling & Privacy
| Question | Response | Supporting Documentation |
|----------|----------|------------------------|
| Do you have a data retention policy? | ☐ Yes ☐ No | Provide policy document |
| Can you delete our data upon request? | ☐ Yes ☐ No | Deletion procedures |
| Do you process personal data? | ☐ Yes ☐ No | Privacy policy |
| Do you share data with sub-processors? | ☐ Yes ☐ No | Sub-processor list |
| Where is our data stored geographically? | | Data residency map |

### 3.3 Data Loss Prevention
| Question | Response | Solution Details |
|----------|----------|-----------------|
| Do you have data loss prevention (DLP) controls? | ☐ Yes ☐ No | |
| Do you monitor for unauthorized data access? | ☐ Yes ☐ No | |
| Do you have controls to prevent data exfiltration? | ☐ Yes ☐ No | |
| How do you detect and prevent insider threats? | | |

---

## Section 4: Access Controls & Identity Management

### 4.1 Authentication & Authorization
| Question | Response | Implementation Details |
|----------|----------|----------------------|
| Do you require multi-factor authentication (MFA)? | ☐ Yes ☐ No ☐ Optional | For which users: |
| What authentication methods do you support? | ☐ SAML ☐ OAuth ☐ LDAP ☐ Other | |
| Do you support single sign-on (SSO)? | ☐ Yes ☐ No | Compatible providers: |
| Do you implement role-based access controls (RBAC)? | ☐ Yes ☐ No | |
| How often do you review user access rights? | ☐ Monthly ☐ Quarterly ☐ Annually ☐ Ad-hoc | |

### 4.2 Privileged Access Management
| Question | Response | Controls In Place |
|----------|----------|------------------|
| How do you manage administrative accounts? | | |
| Do you have a privileged access management (PAM) solution? | ☐ Yes ☐ No | |
| Do you record privileged user sessions? | ☐ Yes ☐ No | |
| How do you control emergency access procedures? | | |

### 4.3 Account Lifecycle Management
| Question | Response | Process Documentation |
|----------|----------|---------------------|
| How quickly can you provision new user accounts? | | |
| How quickly can you disable accounts when needed? | | |
| Do you have automated account provisioning/deprovisioning? | ☐ Yes ☐ No | |
| How do you handle account access for terminated employees? | | |

---

## Section 5: Infrastructure & Cloud Security

### 5.1 Cloud Infrastructure
| Question | Response | Provider Details |
|----------|----------|-----------------|
| What cloud providers do you use? | ☐ AWS ☐ Azure ☐ GCP ☐ Other | |
| Are you using shared or dedicated infrastructure? | ☐ Shared ☐ Dedicated ☐ Hybrid | |
| Do you have multi-region deployments? | ☐ Yes ☐ No | Regions: |
| How do you ensure data residency requirements? | | |

### 5.2 Network Security
| Question | Response | Configuration Details |
|----------|----------|---------------------|
| Do you use firewalls and network segmentation? | ☐ Yes ☐ No | |
| Do you have intrusion detection/prevention systems? | ☐ Yes ☐ No | |
| Do you perform regular network security scans? | ☐ Yes ☐ No | Frequency: |
| How do you secure remote access? | ☐ VPN ☐ Zero Trust ☐ Other | |

### 5.3 Endpoint Security
| Question | Response | Solution Used |
|----------|----------|---------------|
| Do you use endpoint detection and response (EDR)? | ☐ Yes ☐ No | |
| Do you have mobile device management (MDM)? | ☐ Yes ☐ No | |
| What anti-malware solutions do you use? | | |
| Do you encrypt employee devices? | ☐ Yes ☐ No | |

---

## Section 6: Monitoring & Incident Response

### 6.1 Security Monitoring
| Question | Response | Tools/Capabilities |
|----------|----------|-------------------|
| Do you have a Security Operations Center (SOC)? | ☐ Internal ☐ Outsourced ☐ No | |
| Do you use Security Information and Event Management (SIEM)? | ☐ Yes ☐ No | Platform: |
| What is your log retention period? | | |
| Do you monitor for advanced persistent threats? | ☐ Yes ☐ No | |

### 6.2 Incident Response
| Question | Response | Documentation |
|----------|----------|---------------|
| Do you have a formal incident response plan? | ☐ Yes ☐ No | |
| How quickly do you detect security incidents? | ☐ <1 hour ☐ 1-4 hours ☐ 4-24 hours ☐ >24 hours | |
| How quickly do you notify customers of incidents affecting them? | | |
| When did you last test your incident response procedures? | | |
| Have you experienced any security incidents in the past 2 years? | ☐ Yes ☐ No | If yes, please describe: |

### 6.3 Business Continuity
| Question | Response | Testing Frequency |
|----------|----------|------------------|
| Do you have a business continuity plan? | ☐ Yes ☐ No | |
| Do you have a disaster recovery plan? | ☐ Yes ☐ No | |
| What is your Recovery Time Objective (RTO)? | | |
| What is your Recovery Point Objective (RPO)? | | |
| When did you last test your DR procedures? | | |

---

## Section 7: Third-Party Risk Management

### 7.1 Vendor Management
| Question | Response | Details |
|----------|----------|---------|
| Do you conduct security assessments of your vendors? | ☐ Yes ☐ No | |
| Do you require security certifications from your vendors? | ☐ Yes ☐ No | |
| Do you have contracts with security requirements for vendors? | ☐ Yes ☐ No | |
| Please list any sub-processors who will have access to our data: | | |

### 7.2 Supply Chain Security
| Question | Response | Controls |
|----------|----------|----------|
| How do you secure your software development lifecycle? | | |
| Do you use third-party code or open source components? | ☐ Yes ☐ No | |
| How do you manage vulnerabilities in third-party components? | | |
| Do you perform security testing on third-party integrations? | ☐ Yes ☐ No | |

---

## Section 8: Physical & Environmental Security

### 8.1 Facility Security
| Question | Response | Details |
|----------|----------|---------|
| How do you control physical access to facilities? | | |
| Do you have security cameras and monitoring? | ☐ Yes ☐ No | |
| How do you secure server rooms and data centers? | | |
| Do you have environmental controls (fire, flood, power)? | ☐ Yes ☐ No | |

### 8.2 Asset Management
| Question | Response | Process |
|----------|----------|---------|
| Do you have an asset inventory system? | ☐ Yes ☐ No | |
| How do you handle equipment disposal? | | |
| Do you have clean desk/clear screen policies? | ☐ Yes ☐ No | |

---

## Section 9: Application Security

### 9.1 Secure Development
| Question | Response | Implementation |
|----------|----------|---------------|
| Do you follow secure coding practices? | ☐ Yes ☐ No | |
| Do you perform code reviews? | ☐ Yes ☐ No | |
| Do you use static/dynamic application security testing? | ☐ Yes ☐ No | Tools: |
| Do you perform penetration testing? | ☐ Yes ☐ No | Frequency: |

### 9.2 API Security
| Question | Response | Security Measures |
|----------|----------|------------------|
| How do you authenticate API requests? | | |
| Do you implement rate limiting on APIs? | ☐ Yes ☐ No | |
| How do you validate input to prevent injection attacks? | | |
| Do you log and monitor API usage? | ☐ Yes ☐ No | |

---

## Section 10: Legal & Contractual

### 10.1 Data Processing Agreements
| Question | Response | Documentation |
|----------|----------|---------------|
| Are you willing to sign a Data Processing Agreement (DPA)? | ☐ Yes ☐ No | |
| Are you willing to sign a Business Associate Agreement (BAA)? | ☐ Yes ☐ No ☐ N/A | |
| Do you have cyber liability insurance? | ☐ Yes ☐ No | Coverage amount: |
| What are your liability limitations? | | |

### 10.2 Audit Rights
| Question | Response | Process |
|----------|----------|---------|
| Do you allow customer security audits? | ☐ Yes ☐ No ☐ Limited | |
| Can you provide SOC 2 reports in lieu of audits? | ☐ Yes ☐ No | |
| How often can customers request audits? | | |
| What are the costs associated with customer audits? | | |

---

## Supporting Documentation Checklist

**Required Documents:**
- [ ] Current security certifications (SOC 2, ISO 27001, etc.)
- [ ] Most recent penetration test report (executive summary)
- [ ] Data processing/sub-processor list
- [ ] Privacy policy and data retention policy
- [ ] Sample security incident notification
- [ ] Business continuity/disaster recovery summary

**Optional Documents:**
- [ ] Security policy framework overview
- [ ] Employee security training program description
- [ ] Vendor risk management process
- [ ] Physical security controls description

---

## Internal Assessment (For Company Use Only)

### Risk Scoring
| Category | Score (1-5) | Weight | Weighted Score | Notes |
|----------|-------------|--------|----------------|--------|
| Data Security | | 30% | | |
| Access Controls | | 20% | | |
| Compliance | | 20% | | |
| Incident Response | | 15% | | |
| Business Continuity | | 10% | | |
| Physical Security | | 5% | | |
| **Total Risk Score** | | | **/5.0** | |

### Recommendation
- ☐ **Approve**: Low risk, standard contract terms
- ☐ **Approve with Conditions**: Medium risk, enhanced contract terms required
- ☐ **Further Due Diligence**: High risk, additional assessment needed
- ☐ **Reject**: Unacceptable risk level

### Required Actions Before Contract Execution
- [ ] [Action item]
- [ ] [Action item]
- [ ] [Action item]

---

## Review Information

**Questionnaire Version**: ___________
**Vendor Response Date**: ___________
**Internal Review Date**: ___________
**Reviewed By**: _______________
**Approved By**: _______________ **Date**: ___________
**Next Review Date**: ___________
