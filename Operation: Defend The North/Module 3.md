# Operation: Defend The North – Tabletop Simulation Analysis #
## Module 3: Cyberattack on Government – A Nation at Risk ##

### Town: 37 Lakes ###

**📌 Overview**

This tabletop simulation explored a government-level cyber incident impacting a municipality of 250,000 residents in the town of 37 Lakes, located near the region affected by the Appointment 2 pharmacy crisis.

The government’s pre-authorized tax payment system failed, causing citizens to miss tax withdrawals and receive collection calls. Unlike past modules where organizations discovered the incident internally, this module focuses on information spreading rapidly, resulting in council pressure, heightened scrutiny, and the need for transparent public communication.

The goal of this exercise was to assess incident response maturity, vendor accountability, public sector communication, and government crisis readiness.

### 1. Incident Summary ###

The municipality’s automated tax payment system stopped processing payments due to a reactive security action taken by the Security Operations Center (SOC).

During this period, it was discovered that an external actor logged into the environment using root-level access. As a precaution, the system’s connectivity was shut off to prevent further compromise.

**Key issues observed:**
- Pre-authorized tax payments not processed
- Citizens receiving incorrect collection notices
- Evidence of unauthorized root-level login
- Potential mismanagement of private/master keys
- Concern of a supply chain compromise through a vendor software package

**Lack of clarity about whether this is a malfunction, breach, or attack**
**Municipal leadership and council demand answers as concerns spread quickly among residents.**

### 2. News Headline Simulation ###

**“Cyber Issue Halts Tax Processing: Residents Unable to Verify Payment Status, Council Demands Rapid Response.”**

A system failure has interrupted pre-authorized tax payments, raising concerns about financial administration integrity in the town of 37 Lakes.

--- 

**3. Key Participants and Their Roles**
| Role                                | Responsibilities in Simulation                                                                        |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Incident Response Lead / CIO**| Lead technical response, root cause analysis, authentication investigation, change management review. |
| **CEO (Municipal Executive)** |	Governance oversight, ensures transparency with council and public. |
| **Third-Party Vendor Manager** |	Manage vendor investigations, configuration review, remediation guidance, communication with service providers. |
| **Mayor** |	Public reassurance, political leadership, executive oversight. |
| **Council** | Demand accountability, request updates, pressure for resolution. |
| **Public Relations Officer** |	Draft public messaging, coordinate with provincial and federal authorities, manage citizen communication. |
| **Investigator** | 	Log analysis, traffic review, and validation of potential exfiltration. |
| **Industry Expert RZ (Kaspersky)** | 	Analyze root access misuse, confirm supply chain indicators, review key mismanagement issues. |
| **Industry Expert Alice (TELUS)** | Provide telecommunications and infrastructure insight, evaluate potential external access vectors. |

---

### 4. Timeline Analysis ###
**T+0–30 Minutes**
- Pre-authorized payment failures detected.
- Citizens report missing withdrawals and receive collection calls.
- System connectivity shut down after detecting root login from external source.
- Initial confusion between malfunction vs. security breach.

**T+30–60 Minutes**
- CIO initiates authentication investigation.
- Industry expert identifies presence of plaintext master/private key, raising red flags.
- Vendor Manager checks for configuration changes or corrupted package delivery.
- Public pressure increases as rumors spread.

**T+60–90 Minutes**
- Incident appears consistent with a possible supply chain compromise.
- Investigators review inbound/outbound logs for signs of exfiltration.
- Third-party accountability questioned due to inappropriate root access.
- Municipality considers rollback as no containment measures have yet been applied.
- Council demands a formal briefing.

---

**5. Technical Findings**
-Root Cause Suspicions
- Unauthorized user accessed system with root privileges
- Mismanaged private/master keys present in plaintext
- Possible corrupted or vulnerable vendor package, suggesting supply chain compromise
- SOC's reactive actions may have unintentionally triggered system failure
- No proof yet of lateral movement or confirmed exfiltration

**Systems Observed**
- Pre-authorized tax payment system: Non-functional
- Financial records: Possibly incomplete
- Authentication logs: Evidence of external root login

**Network traffic: Under investigation for abnormal outbound connections**

**Key Technical Actions**
- Full authentication audit initiated
- Log review for indicators of compromise
- Traffic analysis for exfiltration suspicion
- Vendor contacted for configuration validation
- Change management review requested by CIO
- Rollback preparation underway

**6. Identity & Access Management Considerations**
- Root access granted to vendor may conflict with best practices
- Need to validate whether access was part of change management or unauthorized
- Assessment required for all privileged access pathways
- Recommendation for strict governance of private keys and encryption materials

### 7. Privacy & Compliance Considerations ###
- No confirmed data breach, but potential exists due to unauthorized root access
- Communications must avoid premature breach declaration
- Public sector obligations require immediate reporting if exfiltration is confirmed
- Council expects transparency but within compliance guidelines

### 8. Public Relations & Communications Strategy ###
- Rapid communication to reassure residents and avoid misinformation
- Messaging coordinated with provincial and federal partners
- Transparency emphasized without disclosing unverified breach details

**PR focuses on:**
- What happened
- What residents should expect
- Who is involved in the investigation
- Commitment to restoring trust and safeguarding taxpayer data

### 9. Business & Government Impact ###
- Halted tax payment processing
- Citizens falsely flagged for collections
- Reputational risk for municipal leadership
- Pressure from council and political stakeholders
- Possible financial discrepancies requiring reconciliation
- Erosion of public trust in government IT systems

### 10. Lessons Learned & Recommendations ###

**Technical**
- Eliminate plaintext master/private keys
- Strengthen authentication logging and privileged access monitoring
- Implement controlled vendor access without shared root accounts
- Improve SOC response procedures to prevent reactive system failures

**Identity & Access Governance**
- Establish strict policies for privileged third-party access
- Enforce key rotation and encryption-management practices
- Review vendor implementation roles to avoid unnecessary elevated permissions

**Communications**
- Maintain prepared crisis communication templates for government use
- Ensure PR teams can engage residents quickly and clearly during outages

**Third-Party Management**
- Demand stronger vendor accountability
- Require validation of update integrity and package authenticity
- Align contract SLAs with security and crisis expectations

**Government Continuity**
- Strengthen municipal DRP and BCP plans
- Improve backup processes for tax systems
- Conduct regular cybersecurity tabletop exercises for council and leadership

### 11. Conclusion ###

This exercise highlights the deep risks associated with cyber incidents in government systems—particularly those involving financial operations and citizen services.

**The incident demonstrates the need for:**

**✔ Stronger authentication controls**

**✔ Clear vendor accountability**

**✔ Robust public communication**

**✔ Improved SOC procedures**

**✔ Mature identity and key management**

The town of 37 Lakes must reinforce its cyber resilience to protect public trust and maintain continuity of essential government services.
