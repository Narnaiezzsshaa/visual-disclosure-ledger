# 🕵️‍♀️ Privacy Impact Assessment (PIA)

## Purpose
Systematic evaluation of privacy risks for new or modified data processing activities, ensuring compliance with privacy regulations and organizational policies.

## When to Complete This Assessment
- New data collection or processing activities
- Significant changes to existing data flows
- New vendor relationships involving personal data
- Technology implementations affecting personal data
- Before launching customer-facing applications

## Project Information

| Field | Details |
|-------|---------|
| **Project Name** | |
| **Project Owner** | |
| **Business Sponsor** | |
| **Assessment Date** | |
| **Target Implementation** | |
| **Regulatory Framework** | ☐ HIPAA ☐ GDPR ☐ CCPA ☐ Other: _____ |

## Data Inventory

### Personal Data Elements

| Data Element | Sensitivity Level | Source | Collection Method | Purpose | Legal Basis |
|--------------|-------------------|--------|-------------------|---------|-------------|
| Full Name | Medium | Registration Form | Direct input | Identity verification | Consent |
| Email Address | Medium | Website | Direct input | Communication | Legitimate interest |
| Social Security Number | High | Intake Form | Direct input | Identity verification | Legal obligation |
| Medical Record Number | High | EHR System | System generated | Healthcare delivery | Consent |
| IP Address | Low | Web logs | Automatic | Security monitoring | Legitimate interest |
| Device Identifiers | Low | Mobile app | Automatic | App functionality | Consent |

### Special Categories (Sensitive Data)
- [ ] Health information (PHI)
- [ ] Racial or ethnic origin
- [ ] Political opinions
- [ ] Religious beliefs
- [ ] Trade union membership
- [ ] Genetic data
- [ ] Biometric data
- [ ] Sexual orientation
- [ ] Criminal history

### Data Subjects
- [ ] Patients/customers
- [ ] Employees
- [ ] Vendors/partners
- [ ] Website visitors
- [ ] Minors (under 18)
- [ ] Vulnerable populations

## Data Processing Activities

### Collection
| Question | Answer | Risk Level |
|----------|---------|------------|
| What personal data is collected? | | |
| Is collection necessary for the stated purpose? | ☐ Yes ☐ No | |
| Is data minimization practiced? | ☐ Yes ☐ No | |
| Are individuals informed about collection? | ☐ Yes ☐ No | |
| Is consent obtained when required? | ☐ Yes ☐ No ☐ N/A | |

### Use and Processing
| Question | Answer | Risk Level |
|----------|---------|------------|
| How is the data used? | | |
| Is use compatible with collection purpose? | ☐ Yes ☐ No | |
| Who has access to the data? | | |
| Are automated decisions made about individuals? | ☐ Yes ☐ No | |
| Is profiling conducted? | ☐ Yes ☐ No | |

### Sharing and Disclosure
| Question | Answer | Risk Level |
|----------|---------|------------|
| Is data shared with third parties? | ☐ Yes ☐ No | |
| What is the legal basis for sharing? | | |
| Are data sharing agreements in place? | ☐ Yes ☐ No ☐ N/A | |
| Is data transferred internationally? | ☐ Yes ☐ No | |
| What safeguards are in place for transfers? | | |

### Storage and Retention
| Question | Answer | Risk Level |
|----------|---------|------------|
| Where is data stored? | | |
| What security measures protect the data? | | |
| How long is data retained? | | |
| Is there a documented retention schedule? | ☐ Yes ☐ No | |
| How is data securely disposed of? | | |

## Risk Assessment

### Likelihood and Impact Matrix

| Risk Scenario | Likelihood (1-5) | Impact (1-5) | Risk Score | Mitigation Priority |
|---------------|------------------|--------------|------------|-------------------|
| Unauthorized access to PHI | 3 | 5 | 15 | High |
| Data breach during transmission | 2 | 4 | 8 | Medium |
| Inadequate consent for processing | 4 | 3 | 12 | High |
| Non-compliance with retention policies | 3 | 3 | 9 | Medium |
| Vendor data misuse | 2 | 4 | 8 | Medium |

**Risk Scoring**: 1-5 (Low), 6-10 (Medium), 11-15 (High), 16-25 (Critical)

### Identified Privacy Risks

#### Risk #1: [Description]
- **Affected Data**: [Types of personal data at risk]
- **Potential Impact**: [Harm to individuals, organization]
- **Current Controls**: [Existing safeguards]
- **Residual Risk**: [Low/Medium/High after controls]

#### Risk #2: [Description]
*[Repeat for each identified risk]*

## Individual Rights Impact

| Right | Affected? | How Supported | Procedure Location |
|-------|-----------|---------------|-------------------|
| **Right to be informed** | ☐ Yes ☐ No | Privacy notice, consent forms | |
| **Right of access** | ☐ Yes ☐ No | Data subject request process | |
| **Right to rectification** | ☐ Yes ☐ No | Update procedures | |
| **Right to erasure** | ☐ Yes ☐ No | Deletion procedures | |
| **Right to restrict processing** | ☐ Yes ☐ No | Processing controls | |
| **Right to data portability** | ☐ Yes ☐ No | Export functionality | |
| **Right to object** | ☐ Yes ☐ No | Opt-out mechanisms | |
| **Rights related to automated decision-making** | ☐ Yes ☐ No ☐ N/A | Review procedures | |

## Mitigation Measures

| Risk | Mitigation Measure | Owner | Implementation Date | Status |
|------|-------------------|-------|-------------------|--------|
| Unauthorized access | Implement role-based access controls | IT Security | MM/DD/YYYY | ☐ Planned ☐ In Progress ☐ Complete |
| Data retention | Automated deletion after retention period | Data Engineering | MM/DD/YYYY | ☐ Planned ☐ In Progress ☐ Complete |
| Vendor oversight | Enhanced due diligence and BAA | Legal/Procurement | MM/DD/YYYY | ☐ Planned ☐ In Progress ☐ Complete |

## Consultation and Review

### Stakeholder Consultation
- [ ] Data Protection Officer
- [ ] Legal counsel
- [ ] IT Security team
- [ ] Business stakeholders
- [ ] Affected departments

### External Consultation
- [ ] Data subjects (where appropriate)
- [ ] Industry experts
- [ ] Regulatory authorities
- [ ] Privacy advocacy groups

## Decision and Approval

### Risk Acceptance
Based on this assessment:
- [ ] Risks are acceptable with current controls
- [ ] Risks are acceptable with additional mitigation measures
- [ ] Risks are unacceptable; project should not proceed as planned
- [ ] Requires further analysis or consultation

### Recommendations
1. [Specific recommendation]
2. [Specific recommendation]
3. [Specific recommendation]

### Monitoring and Review
- **Review Frequency**: [Quarterly/Semi-annually/Annually]
- **Key Performance Indicators**: [Metrics to track]
- **Review Triggers**: [Events that require reassessment]

## Signatures

**Completed By**: _______________  **Date**: ___________  **Role**: _______________

**Reviewed By**: _______________  **Date**: ___________  **Role**: _______________

**Approved By**: _______________  **Date**: ___________  **Role**: _______________

## Supporting Documents
- [ ] Privacy notice
- [ ] Consent forms
- [ ] Data sharing agreements
- [ ] Vendor contracts
- [ ] Security documentation
- [ ] Retention schedules
