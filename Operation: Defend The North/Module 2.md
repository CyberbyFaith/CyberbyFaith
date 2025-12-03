Operation: Defend The North – Tabletop Simulation Analysis
Module 2: Cyberattack on Healthcare – Pharmacy Sector in Crisis

Company: Appointment 2

📌 Overview

This tabletop simulation explored a major outage affecting the only pharmacy service in a town of 150,000 residents. Appointment 2 operates three locations and provides essential prescription and healthcare services.

A sudden system disruption prevented payment processing, caused loss of financial reporting data, and threatened patient access to critical medications. The purpose of this exercise was to analyze incident response, cross-team coordination, public communication, and crisis management in a healthcare-focused cyber scenario.

1. Incident Summary

Appointment 2 experienced a failure across its payment and reporting systems following a recent update pushed by a third-party vendor.

Key symptoms included:

Inability to transact payments across multiple branches

Missing or incomplete financial reporting data

Vendor maintenance activities possibly linked to the disruption

Shadow IT applications previously identified as a risk factor

No confirmation yet whether this is a breach, malfunction, or security incident

The outage created significant risk to patients, disrupted access to medication, affected revenue, and triggered community concern.

2. News Headline Simulation

“Cyber Incident Halts Prescription Refills and Essential Purchases: Patients Unable to Access Critical Medication.”
A system malfunction has impacted pharmacies, preventing payment transactions and essential healthcare services across the community.

3. Key Participants and Their Roles
Role	Responsibilities in Simulation
IT Security Team Lead	Review EDR alerts, analyze architecture diagrams, assess vendor integrations, track vulnerabilities.
CISO	Evaluate potential breach indication, manage executive communication, assess DRP/BCP activation.
Business Development Manager	Oversight of customer trust, reputation impacts, and prescription service communication.
IT Manager	Coordinate with vendor on update rollback, restore services, manage shadow IT complications.
Incident Commander	Maintain update cadence, coordinate IR team, evaluate contingency and continuity plans.
Government Relations Officer	Engage government healthcare services, coordinate medication distribution during outage.
Communications Lead	Align messaging with hospitals/government, manage public communication during crisis.
Canon (Industry Expert)	Provide technical diagnostics, onsite reboot support, backup/security alert forwarding.
SailPoint (Identity Governance Expert)	Review privileged access, track vendor access, ensure governed identity lifecycle.
4. Timeline Analysis
T+0–30 Minutes

Outage detected across pharmacy branches.

Payment terminals unable to process transactions.

Technical team and vendor begin diagnostics.

Concern arises over missing financial reporting data.

Early suspicion: failed update or network issue.

T+30–60 Minutes

Vendor involved for root cause analysis.

IT Security advises against shutting down systems to preserve log integrity.

Shadow IT identified as a contributing factor.

Healthcare impact escalates—patients unable to access medication.

T+60–90 Minutes

Community frustration increasing.

Government support considered for emergency medication distribution.

Incident Commander drafts initial recovery options.

Consideration of rollback, emergency mode, or temporary bypass of batch processes.

CISO begins breach assessment and possible legal communication planning.

5. Technical Findings
Root Cause Suspicions

Failed update pushed by third-party vendor

Disrupted financial batch processes

API or middleware communication breakdown

Potential unintended blocking by internal security tools

No confirmed evidence of an external threat actor

Systems Observed

Payment systems: Online but unable to complete transactions

Financial reports: Missing/incomplete

Pharmacy operations: Medication distribution halted

Shadow IT application: Contributing factor to instability

Key Technical Actions

Vendor contacted for rollback feasibility

Backup restoration considered

EDR and infrastructure alerts re-evaluated

Canon dispatched onsite for diagnostics and reboot support

Analysis of architecture diagrams and network flow initiated

6. Identity & Access Management Review (SailPoint Input)

Third-party privileged identities reviewed for governance gaps

Access of external vendors monitored and validated

Recommendation to apply stricter lifecycle management to contractors

No identity misuse detected at this stage

7. Privacy & Compliance Considerations

No confirmation of a privacy breach

CISO preparing breach communication plan only if evidence emerges

Legal counsel recommended before any public breach disclosure

Compliance teams on standby

8. Public Relations & Communications Strategy

Unified messaging coordinated with hospitals and government agencies

Communications Lead monitors public sentiment and prepares guidance

Emergency services considered (EMTs, hospital staff, alternate pharmacies)

Focus on maintaining trust and addressing patient safety concerns

9. Business Impact

Complete halt of digital payments

Delayed or unavailable prescription access

Significant reputational risk

Loss of revenue and customer trust

Operational downtime across two pharmacy branches

Potential escalation to public health emergency

10. Lessons Learned & Recommendations
Technical

Implement safer deployment and rollback procedures

Improve API/middleware monitoring

Strengthen architecture documentation and vendor integration mapping

Identity & Access

Enforce strict privileged access governance for third parties

Ensure timely deprovisioning of vendor access

Conduct more frequent identity audits

Communications

Improve community communication playbooks for healthcare outages

Establish rapid escalation paths with hospitals and government partners

Third-Party Management

Review vendor SLAs regarding updates, rollback, and maintenance

Adopt stricter oversight and validation of vendor patches

Business Continuity

Create redundancy for pharmacy payment systems

Develop emergency medication distribution workflows

Enhance DRP and BCP testing for healthcare-specific scenarios

11. Conclusion

This simulation highlights the severe impact of system outages on healthcare delivery and patient safety. It demonstrates the importance of:

✔ Coordinated multi-team response
✔ Strong identity governance
✔ Transparent communication with the public
✔ Vendor oversight and shadow IT prevention
✔ Effective business continuity planning

Appointment 2 must strengthen its technical, operational, and governance posture to ensure resilience and safeguard critical healthcare services in future crises.
