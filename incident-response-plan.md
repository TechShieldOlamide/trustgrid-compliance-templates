# Incident Response Plan Template

> **TrustGrid Compliance Template** — Customise all [PLACEHOLDER] fields before use.
> Created by [TrustGrid Technology Limited](https://trustgridhq.com).

---

## 1. Purpose

This Incident Response Plan (IRP) defines how [COMPANY NAME] identifies, contains, investigates, and recovers from cybersecurity and data protection incidents in accordance with ISO 27001 controls and NDPR/GDPR breach notification requirements.

---

## 2. Scope

This plan covers all security incidents affecting:
- Customer personal data
- Financial and transaction data
- Internal systems and infrastructure
- Third-party integrations and APIs

---

## 3. Incident Classification

| Severity | Description | Response Time |
|----------|-------------|---------------|
| Critical (P1) | Data breach, ransomware, system compromise | Immediate — within 1 hour |
| High (P2) | Unauthorized access, significant data exposure | Within 4 hours |
| Medium (P3) | Suspicious activity, minor data exposure | Within 24 hours |
| Low (P4) | Policy violations, minor anomalies | Within 72 hours |

---

## 4. Incident Response Team

| Role | Name | Contact |
|------|------|---------|
| Incident Response Lead | [NAME] | [EMAIL/PHONE] |
| IT/Security Lead | [NAME] | [EMAIL/PHONE] |
| Data Protection Officer | [NAME] | [EMAIL/PHONE] |
| Legal Counsel | [NAME] | [EMAIL/PHONE] |
| Communications Lead | [NAME] | [EMAIL/PHONE] |
| Senior Management | [NAME] | [EMAIL/PHONE] |

---

## 5. Incident Response Phases

### Phase 1 — Identification

- Monitor alerts from SIEM, IDS/IPS, and endpoint tools
- Receive reports from staff, customers, or third parties
- Validate whether the event constitutes a security incident
- Log the incident in the incident register with timestamp

**Incident Register fields:**
- Incident ID
- Date and time detected
- Reported by
- Systems affected
- Initial description
- Severity classification

### Phase 2 — Containment

**Short-term containment:**
- Isolate affected systems from the network
- Disable compromised accounts
- Block malicious IPs or domains
- Preserve system images and logs for forensic analysis

**Long-term containment:**
- Apply patches or configuration changes
- Implement additional monitoring
- Deploy temporary fixes while permanent solutions are developed

### Phase 3 — Investigation

- Determine the root cause of the incident
- Identify the scope of data or systems affected
- Establish the timeline of events
- Determine whether personal data was accessed, exfiltrated, or destroyed
- Document all findings

### Phase 4 — Notification

#### Internal Notification
- Notify Senior Management within [X] hours of confirmed incident
- Brief the Board if incident is Critical or High severity

#### Regulatory Notification
| Regulation | Authority | Deadline |
|------------|-----------|----------|
| NDPR/NDPA | Nigeria Data Protection Commission (NDPC) | 72 hours of becoming aware |
| GDPR | Relevant EU Supervisory Authority | 72 hours of becoming aware |
| CBN | Central Bank of Nigeria | As per CBN guidelines |

#### Customer Notification
Notify affected customers if:
- Their personal data was compromised
- There is high risk to their rights and freedoms
- Regulatory requirements mandate notification

Notification must include:
- Nature of the breach
- Data categories affected
- Likely consequences
- Measures taken to address the breach
- Contact details for further information

### Phase 5 — Recovery

- Restore systems from clean backups
- Verify system integrity before returning to production
- Monitor systems closely post-recovery
- Confirm no persistence of threat actor

### Phase 6 — Post-Incident Review

Within 2 weeks of incident resolution:
- Conduct a full post-incident review
- Document lessons learned
- Update security controls and procedures
- Provide a final incident report to Senior Management
- Update risk register

---

## 6. Evidence Preservation

All incident-related evidence must be preserved including:
- System logs and audit trails
- Network traffic captures
- Affected system images
- Communications related to the incident

Evidence must be preserved for a minimum of 3 years.

---

## 7. Communication Guidelines

- Do NOT discuss incident details on unsecured channels
- All external communications must be approved by Legal and Senior Management
- Do NOT confirm or deny incidents to media without approval
- Document all internal and external communications

---

## 8. Plan Testing

This plan must be tested:
- Annually through tabletop exercises
- Following any significant incident
- Following major changes to systems or infrastructure

---

## 9. Document Control

**Plan Owner:** [CISO/IT SECURITY LEAD]
**Last Reviewed:** [DATE]
**Next Review:** [DATE]
**Version:** 1.0

---

*This template was created by [TrustGrid Technology Limited](https://trustgridhq.com). Customise to reflect your specific environment and seek qualified security and legal advice before use.*
