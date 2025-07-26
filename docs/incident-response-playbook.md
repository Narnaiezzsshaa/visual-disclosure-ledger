# 🚨 Incident Response Playbook

## Purpose
Coordinate fast, transparent response to security incidents with clear escalation paths and communication protocols.

## Severity Classification

| Severity | Definition | Examples | Initial Response Time |
|----------|------------|----------|----------------------|
| **Low** | Minor issue, no customer impact, limited scope | Failed login attempts, minor config drift | 24 hours |
| **Medium** | Service degradation, internal impact only | API slowdown, internal system outage | 4 hours |
| **High** | Customer impact, potential data exposure | PHI access by unauthorized user, external breach attempt | 1 hour |
| **Critical** | Confirmed data breach, legal/regulatory exposure | Ransomware, confirmed PHI exfiltration, system compromise | 15 minutes |

## Response Timeline & Actions

| Severity | Detection | Confirmation | Escalation | Containment | Recovery | Post-Incident |
|----------|-----------|--------------|------------|-------------|----------|---------------|
| **Low** | 24h | 48h | Internal only | 72h | 5 days | 2 weeks |
| **Medium** | 4h | 8h | IT Manager | 12h | 2 days | 1 week |
| **High** | 1h | 2h | Executive team | 4h | 24h | 72h |
| **Critical** | 15m | 30m | CEO + Legal | 1h | 8h | 48h |

## Decision Tree

### Initial Assessment Questions
1. **Is customer data involved?** → If yes, escalate to High/Critical
2. **Are external systems affected?** → If yes, notify vendors immediately
3. **Is this a suspected attack?** → If yes, preserve evidence before containment
4. **Do we need legal counsel?** → If data breach or regulatory impact, engage legal

### Escalation Triggers
- **Automatically escalate to Critical if:**
  - PHI/PII confirmed accessed by unauthorized parties
  - Ransomware or malware detected
  - External threat actor confirmed in environment
  - Regulatory notification requirements triggered

## Communication Protocols

### Internal Notification (Required)
- **Immediate**: Security team, IT Manager
- **Within 1 hour**: Executive team (High/Critical only)
- **Within 4 hours**: All staff (Critical only)

### External Notification (As Required)
- **Customers**: Within 24-72 hours depending on impact
- **Vendors**: Immediately if their systems affected
- **Regulatory**: Per legal requirements (typically 72 hours)
- **Law Enforcement**: For criminal activity or as legally required

## Communication Templates

### Internal Alert (Slack/Teams)
```
🚨 SECURITY INCIDENT - [SEVERITY LEVEL]

SUMMARY: [Brief description]
AFFECTED SYSTEMS: [List]
CUSTOMER IMPACT: [Yes/No + details]
ESTIMATED RESOLUTION: [Timeframe]
INCIDENT COMMANDER: [@person]
NEXT UPDATE: [When]

DO NOT discuss this incident outside authorized channels.
```

### Executive Notification (Email)
```
Subject: URGENT - Security Incident Requiring Executive Attention

INCIDENT: [Brief description]
SEVERITY: [Level + justification]
BUSINESS IMPACT: [Revenue, reputation, regulatory]
CUSTOMER IMPACT: [Scope and severity]
CONTAINMENT STATUS: [Actions taken]
NEXT STEPS: [Immediate priorities]
LEGAL CONSIDERATIONS: [If applicable]

This incident requires executive decision-making on [specific decisions needed].
```

### Customer Communication (Email)
```
Subject: Important Security Update - [Company Name]

Dear [Customer Name],

We are writing to inform you of a security incident that may have affected your data. We take the security of your information seriously and want to provide you with the details.

WHAT HAPPENED: [Clear, non-technical explanation]
WHAT INFORMATION WAS INVOLVED: [Specific data types]
WHAT WE ARE DOING: [Response actions taken]
WHAT YOU CAN DO: [Specific recommendations]

We sincerely apologize for this incident and any inconvenience it may cause. If you have questions, please contact us at [contact information].

[Name and Title]
```

### Regulatory Notification Template
```
BREACH NOTIFICATION - [Regulation] Compliance

Entity: [Company Name]
Date of Discovery: [Date]
Date of Breach: [Estimated date]
Type of Information: [PHI/PII categories]
Estimated Individuals Affected: [Number or "under investigation"]
Summary of Incident: [Factual description]
Remediation Actions: [Steps taken]
Contact Information: [Incident response contact]
```

## Incident Commander Checklist

### Immediate Actions (0-30 minutes)
- [ ] Confirm incident severity and classification
- [ ] Establish incident command center (conference bridge)
- [ ] Document all actions in incident log
- [ ] Preserve evidence before containment actions
- [ ] Notify required internal stakeholders

### Short-term Actions (30 minutes - 4 hours)
- [ ] Implement containment measures
- [ ] Assess scope and impact
- [ ] Engage external resources if needed (legal, forensics, vendors)
- [ ] Prepare initial stakeholder communications
- [ ] Begin recovery planning

### Recovery Actions (4+ hours)
- [ ] Execute recovery procedures
- [ ] Monitor for incident recurrence
- [ ] Document lessons learned
- [ ] Update procedures based on response effectiveness
- [ ] Schedule post-incident review meeting

## Post-Incident Review

**Timeline**: Within 5 business days of incident resolution

**Required Attendees**: Incident response team, affected system owners, management

**Review Topics**:
- Response timeline effectiveness
- Communication clarity and timeliness
- Technical containment and recovery
- Policy/procedure gaps identified
- Recommendations for improvement

**Deliverable**: Post-incident report with specific action items and owners
