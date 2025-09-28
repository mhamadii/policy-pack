# Incident Response Plan (IRP)

## Purpose
This Incident Response Plan provides structured guidance for identifying, analyzing, containing, eradicating, and recovering from security incidents. The plan is aligned with NIST CSF and ISO 27001 best practices.

## Scope
Applies to all employees, contractors, and third parties who access company IT systems, data, and networks.

---

## Incident Response Lifecycle

### 1. Preparation
- Train staff on security awareness and incident reporting procedures.
- Maintain updated contact list of IT, SOC, and executive stakeholders.
- Ensure logging, monitoring, and alerting tools are active.

### 2. Identification
- Detect potential incidents via SIEM alerts, user reports, or monitoring tools.
- Classify severity (Low, Medium, High, Critical).
- Document all findings in the incident tracking system.

### 3. Containment
- Short-term: isolate affected systems from the network.
- Long-term: apply patches, reconfigure firewalls, or disable compromised accounts.

### 4. Eradication
- Remove malware, unauthorized users, or malicious code.
- Apply forensic analysis to confirm all threats are eliminated.

### 5. Recovery
- Restore systems from clean backups.
- Monitor systems for signs of re-infection or persistence.
- Validate business operations return to normal.

### 6. Lessons Learned
- Conduct post-incident review within 7 days.
- Document timeline, root cause, and impact.
- Update playbooks, policies, and detection rules.

---

## Roles & Responsibilities
- **Incident Response Lead (SOC Manager):** Oversees coordination and decision-making.
- **System Administrators:** Execute containment, eradication, and recovery tasks.
- **Legal & Compliance:** Ensure regulatory obligations (e.g., HIPAA, GDPR) are met.
- **Executive Leadership:** Approve escalations and external communications.

---

## Communication Plan
- Notify SOC team immediately upon detection.
- Escalate high/critical incidents to executive management.
- Coordinate with legal/compliance before external disclosures.
- Use pre-approved templates for customer or regulator notifications.

---

## Metrics & Reporting
- Mean Time to Detect (MTTD)
- Mean Time to Respond (MTTR)
- Number of incidents by severity
- Compliance with SLA timelines
