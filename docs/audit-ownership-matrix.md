# 🧮 Audit Ownership Matrix

## Purpose
Clarifies audit responsibilities across internal teams, vendors, and shared environments. Supports modular reuse, evidence mapping, and emotionally literate stewardship.

## Completion Guidance
- Use RACI logic: **Responsible** = executes the work; **Accountable** = signs off and ensures completion; **Consulted** = provides input; **Informed** = kept in the loop
- Start with known controls from your Compliance Checklist or vendor questionnaire
- Map shared responsibilities in hybrid or co-managed environments
- Review quarterly to align with stewardship cycles and organizational changes
- Link to SOPs, contracts, or audit logs in adjacent columns if needed

## RACI Matrix

| Audit Domain | Responsible | Accountable | Consulted | Informed | Evidence Location | Review Frequency |
|--------------|-------------|-------------|-----------|----------|-------------------|------------------|
| **Access Controls** | | | | | | |
| - User provisioning | IT Admin | IT Manager | HR, Security Lead | Department Heads | IAM system logs | Monthly |
| - Privileged access review | Security Lead | CISO | IT Manager | Executives | PAM audit reports | Monthly |
| - Access certification | Department Heads | IT Manager | HR | Compliance Officer | Access review reports | Quarterly |
| **Data Protection** | | | | | | |
| - Encryption implementation | DevOps Lead | IT Manager | Security Lead | Compliance Officer | Encryption reports | Quarterly |
| - Data classification | Data Owner | Data Protection Officer | Legal | IT Security | Classification logs | Semi-annually |
| - Backup verification | Backup Admin | IT Manager | Business Units | Executive Team | Backup test reports | Monthly |
| **Vendor Management** | | | | | | |
| - Vendor risk assessment | Procurement | Risk Officer | Legal, IT Security | Business Sponsors | Risk assessment docs | Annually |
| - SLA monitoring | Vendor Manager | Business Owner | IT Operations | Executive Team | SLA reports | Monthly |
| - Contract compliance | Legal | Chief Legal Officer | Procurement | Business Units | Contract reviews | Annually |
| **Incident Response** | | | | | | |
| - Incident detection | SOC Team | Security Lead | IT Operations | IT Manager | SIEM logs | Continuous |
| - Incident coordination | Incident Commander | CISO | Legal, PR | Executive Team | Incident reports | Per incident |
| - Post-incident review | Security Lead | CISO | All responders | Board (if material) | PIR documents | Per incident |
| **Business Continuity** | | | | | | |
| - BCP maintenance | BCP Coordinator | Risk Officer | Department Heads | All Staff | BCP documents | Semi-annually |
| - DR testing | IT Operations | IT Manager | Business Units | Executive Team | DR test reports | Quarterly |
| - Communication protocols | Communications Lead | CEO | Legal, HR | All Stakeholders | Comm plan docs | Annually |
| **Privacy Compliance** | | | | | | |
| - Privacy impact assessments | Privacy Officer | Chief Privacy Officer | Legal, IT | Business Units | PIA documents | Per project |
| - Data subject requests | Customer Service | Privacy Officer | Legal, IT | Compliance Officer | DSR logs | Monthly |
| - Consent management | Marketing/Product | Privacy Officer | Legal | Customer Service | Consent records | Quarterly |
| **Financial Controls** | | | | | | |
| - Expense approvals | Department Managers | CFO | Finance Team | Executives | Approval workflows | Monthly |
| - Audit coordination | Internal Audit | Audit Committee | All Departments | Board | Audit reports | Annually |
| - Compliance reporting | Compliance Officer | Chief Compliance Officer | Legal, Finance | Executives | Compliance reports | Quarterly |

## Shared Responsibility Examples

### Cloud Infrastructure (AWS/Azure/GCP)
| Control Area | Customer Responsibility | Cloud Provider Responsibility | Shared Elements |
|--------------|------------------------|------------------------------|-----------------|
| Infrastructure Security | Configuration, patching guest OS | Physical security, host OS patching | Network controls, access management |
| Data Protection | Data encryption, classification | Infrastructure encryption | Key management, transit security |
| Access Management | User accounts, permissions | Infrastructure access controls | Identity federation, MFA |

### SaaS Applications
| Control Area | Customer Responsibility | Vendor Responsibility | Shared Elements |
|--------------|------------------------|----------------------|-----------------|
| User Management | User provisioning, role assignment | Platform security, access controls | SSO integration, audit logging |
| Data Protection | Data classification, usage policies | Data encryption, backup | Data retention, incident response |
| Compliance | Policy compliance, training | Platform certifications | Audit support, reporting |

## Stewardship Logic & Emotional Hygiene

### Principles for Respectful Audit Ownership
- **Clarity over Control**: Focus on clear expectations rather than rigid authority
- **Dignity in Delegation**: Honor the expertise and autonomy of responsible parties
- **Repair-Oriented**: When issues arise, focus on learning and improvement rather than blame
- **Proportionate Response**: Match the effort to the actual risk and impact

### Common Friction Points & Resolutions
| Friction Point | Root Cause | Resolution Approach |
|----------------|------------|-------------------|
| "Not my job" responses | Unclear ownership or excessive burden | Clarify scope, redistribute workload, provide training |
| Vendor finger-pointing | Ambiguous contract terms | Update contracts, create joint playbooks |
| Audit fatigue | Over-auditing or redundant requests | Consolidate reviews, automate where possible |
| Executive bypass | Lack of buy-in or understanding | Improve communication, demonstrate value |

## Implementation Guidance

### Getting Started
1. **Map Current State**: Document who actually performs each audit function today
2. **Identify Gaps**: Note where responsibility is unclear or unassigned
3. **Assign Ownership**: Use existing roles and expertise, create new roles only if necessary
4. **Document Procedures**: Link each responsibility to specific procedures or SOPs
5. **Communicate Changes**: Ensure all stakeholders understand their roles

### Maintenance
- **Quarterly Reviews**: Update matrix based on organizational changes
- **Annual Deep Dive**: Reassess effectiveness and adjust based on audit findings
- **Continuous Improvement**: Collect feedback from responsible parties and adjust processes

### Success Metrics
- **Audit Findings**: Track reduction in findings related to unclear ownership
- **Response Times**: Monitor improvement in issue resolution times
- **Stakeholder Satisfaction**: Survey responsible parties on clarity and fairness
- **Compliance Scores**: Measure overall compliance posture improvement

## Integration with Other Templates

### Links to Related Documents
- **Compliance Checklist**: Maps to specific audit domains for evidence collection
- **Incident Response Playbook**: Defines roles during security incidents
- **Vendor Risk Assessment**: Informs vendor-related audit responsibilities
- **Data Flow Assessment**: Provides context for data protection audit activities

## Review and Approval

**Matrix Version**: ___________
**Last Updated**: ___________
**Updated By**: _______________
**Next Review Date**: ___________
**Approved By**: _______________ **Date**: ___________

## Action Items

| Issue | Priority | Owner | Due Date | Status |
|-------|----------|-------|----------|--------|
| Define backup admin role | High | IT Manager | MM/DD/YYYY | ⬜ |
| Update vendor SLA monitoring process | Medium | Procurement | MM/DD/YYYY | ⬜ |
| Clarify data classification ownership | Medium | Data Protection Officer | MM/DD/YYYY | ⬜ |
