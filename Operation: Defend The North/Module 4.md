# Operation: Defend the North #
## Cybersecurity in Crisis: Protecting Canada’s Critical Systems ##

### Company: Oath Profit — Incident Response & Cybersecurity Firm ###

**📌 Overview**

Oath Profit is a highly specialized incident response firm frequently retained by breach coaches and consulting companies during major cybersecurity emergencies. In this simulation, the team responded to a nationwide crisis affecting a critical financial system, resulting in widespread outages and operational disruption.

####🧩 Key Participants ###

IT Security Team Lead
Deputy CISO
CISO
Chief Risk Officer
Communications Manager
Client Success Manager
Director of Marketing

### 📰 News Report Summary ###

A temporary shutdown across multiple sectors has caused widespread service disruptions. Businesses are being advised to migrate off affected systems and transition to more stable, secure platforms.

### 🔍 Initial Incident Details

ODTN Financials experienced several days of outages and instability impacting their file-transfer product, which supports:

FTP

SFTP

SSH

An engineering error was discovered during deployment:

Developers created custom encryption libraries inside SSH, intending to improve performance and security.

The custom cryptography caused platform-wide failures, impacting all customers.

🗣️ Key Discussion Points
Communications Manager

Determine what notifications should be sent to clients.

Ensure customers can monitor for suspicious activity and take proactive safety measures.

Deputy CISO

Concerned about legal exposure and upcoming lawsuits.

Stresses urgency: Are all clients impacted? Could dormant systems reveal more failures later?

Emphasizes need for containment and root-cause validation.

Public Relations Officer

Pushes back against speculation.

Highlights boundaries on what must be disclosed publicly versus internally.

Deputy CISO (Further Discussion)

Entire software update process must be revisited:

How updates are executed

Validation methods

Access permissions

Legitimacy of update requests

Personnel involved

Public Relations Officer (Further Communication)

Advocates for transparency:

System recovery timeline

What interim alternatives customers can use

How services can remain operational during outages

IT Security Team Lead

Proposes splitting the team into parallel containment streams:

Stream 1 — Client Impact Analysis

What package was deployed across all customers?

What changes were made?

Did the update introduce vulnerabilities or infection risks?

Is remediation required?

Stream 2 — Internal Cleanup

Stabilize Oath Profit’s own internal systems.

Validate environment integrity.

CISO

Requests updates from third-party vendors.

Pushes for a timeline and clear impact mitigation strategy.

Prioritizes restoring customer functionality.

Deputy CISO

Recommends real-time visibility improvements:

Single source of truth

Environment-wide situational awareness

🛠️ Updated Technical Findings

Root cause traced to:

Misconfigured SSHD settings

Custom cryptographic implementation

Faulty upstream configuration files

Remediation:

Fix SSHD configurations

Push corrected files upstream

Notify all affected clients

Require immediate patching across environments

⚖️ Chief Risk Officer Perspective

Focus on regulatory and compliance exposure

Prepare for legal actions

Demonstrate clear evidence of negligence or malicious activity

Establish transparent, documented remediation strategy

📘 Final Summary for GitHub

This simulation recreated a real-world, large-scale cybersecurity crisis involving:

Failed software deployment

Root-cause analysis

Regulatory and legal implications

Incident response coordination

Vendor management

Executive-level communication

Multi-stream containment strategies

The scenario highlights the importance of:

Strong change-management processes

Secure development practices

Real-time system visibility

Transparent communication

Legal preparedness

Vendor accountability
