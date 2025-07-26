# 🔄 Data Flow Assessment

## Purpose
Map end-to-end data pathways between SMB systems and vendors, documenting transformation, ownership, and stewardship responsibilities.

## Completion Guidance
- Document all data flows involving sensitive information (PII, PHI, financial)
- Update assessment when new integrations are added or modified
- Review quarterly or after significant architecture changes
- Use this assessment to support privacy impact assessments and audit requirements

## Data Classification Schema

| Classification | Definition | Examples | Handling Requirements |
|---------------|------------|----------|----------------------|
| **Public** | Information that can be freely shared | Marketing materials, public documentation | Standard security |
| **Internal** | Information for internal use only | Employee directories, internal policies | Access controls |
| **Confidential** | Sensitive business information | Financial reports, strategic plans | Encryption + access controls |
| **Restricted** | Regulated or highly sensitive data | PHI, PII, payment data | Full encryption + audit logging |

## Data Flow Mapping

### Flow #1: [Name/Description]

| Element | Details | Notes |
|---------|---------|-------|
| **Source System** | [System name and description] | |
| **Data Types** | [Specific data elements] | |
| **Classification** | [Public/Internal/Confidential/Restricted] | |
| **Volume** | [Records per day/month] | |
| **Integration Method** | [API, File transfer, Database sync, etc.] | |
| **Frequency** | [Real-time, Hourly, Daily, etc.] | |
| **Transformation** | [Encryption, Anonymization, Aggregation] | |
| **Intermediate Systems** | [Processing layers, staging areas] | |
| **Destination System** | [Final storage location] | |
| **Data Owner** | 🟢 Internal / 🟠 Vendor / 🔵 Shared | |
| **Retention Period** | [Time period and disposal method] | |
| **Access Controls** | [Who can access, how access is granted] | |
| **Encryption** | [At rest, in transit, key management] | |
| **Backup/Recovery** | [Backup frequency and retention] | |
| **Monitoring** | [Logging, alerting, anomaly detection] | |
| **Breach Impact** | [Low/Medium/High/Critical] | |
| **Regulatory Requirements** | [HIPAA, GDPR, etc.] | |

### Flow #2: [Name/Description]
*[Repeat table structure for each significant data flow]*

## Integration Architecture

### API Endpoints
| Endpoint | Purpose | Authentication | Rate Limits | Data Types |
|----------|---------|----------------|-------------|------------|
| `POST /api/patients` | Patient registration | OAuth 2.0 + TLS | 100/hour | PHI |
| `GET /api/billing` | Billing data retrieval | API Key + TLS | 50/hour | Financial |

### File Transfer Mechanisms
| Method | Schedule | Location | Encryption | File Types |
|--------|----------|----------|------------|------------|
| SFTP | Daily 2 AM | `/secure/imports/` | AES-256 | CSV, XML |
| S3 Upload | Real-time | `s3://bucket/incoming/` | Server-side | JSON |

### Database Connections
| Source DB | Destination | Connection Type | Sync Frequency | Data Scope |
|-----------|-------------|-----------------|----------------|------------|
| PostgreSQL | Vendor DW | Read replica | Every 6 hours | Anonymized analytics |

## Ownership & Stewardship Matrix

| Data Element | Source Owner | Processing Owner | Storage Owner | Access Grantor | Retention Manager |
|--------------|--------------|------------------|---------------|----------------|-------------------|
| Patient Demographics | 🟢 Internal EHR | 🔵 Shared ETL | 🟠 Vendor Cloud | 🟢 Internal IAM | 🟢 Internal Legal |
| Billing Records | 🟢 Internal Billing | 🟢 Internal Finance | 🟢 Internal DB | 🟢 Internal Finance | 🟢 Internal Finance |
| Analytics Data | 🟢 Internal Apps | 🟠 Vendor Analytics | 🟠 Vendor Cloud | 🟠 Vendor Portal | 🔵 Shared Policy |

## Data Lineage Tracking

### Patient Record Journey
1. **Patient Registration** → EHR System (Internal)
2. **Eligibility Check** → Insurance API (External)
3. **Clinical Documentation** → EHR Database (Internal)
4. **Billing Integration** → Revenue Cycle System (Vendor)
5. **Analytics Processing** → Data Warehouse (Vendor)
6. **Reporting** → Business Intelligence (Vendor)

*Document key transformation points and approval gates*

## Risk Assessment

| Flow/Integration | Risk Level | Primary Concerns | Mitigation Measures | Review Date |
|------------------|------------|------------------|---------------------|-------------|
| EHR → Analytics Platform | High | PHI exposure, vendor access | De-identification, BAA, access audits | Quarterly |
| Billing → Payment Processor | Medium | PCI compliance, financial data | Tokenization, PCI-DSS certification | Semi-annually |

## Compliance Mapping

### HIPAA Covered Flows
- [ ] Business Associate Agreements (BAAs) in place
- [ ] Minimum necessary standard applied
- [ ] Access controls and audit logging enabled
- [ ] Encryption requirements met

### GDPR Relevant Flows
- [ ] Lawful basis documented
- [ ] Data subject rights procedures established
- [ ] Cross-border transfer mechanisms (SCCs, adequacy decisions)
- [ ] Data Protection Impact Assessment completed if required

### State Privacy Laws
- [ ] Consumer rights request procedures
- [ ] Data minimization practices implemented
- [ ] Third-party sharing disclosures updated

## Data Flow Diagram

*[Include visual representation of key data flows - can be hand-drawn, Visio, or tool-generated]*

## Action Items

| Issue | Priority | Owner | Due Date | Status |
|-------|----------|-------|----------|--------|
| Missing BAA for Analytics Vendor | High | Legal | MM/DD/YYYY | ⬜ |
| Encryption not enabled for File Transfer | Medium | IT | MM/DD/YYYY | ⬜ |

## Review Information

**Assessment Date**: ___________
**Reviewed By**: _______________
**Next Review Date**: ___________
**Approved By**: _______________ **Date**: ___________
