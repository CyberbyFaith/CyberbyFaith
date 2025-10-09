NIST Cybersecurity Framework (CSF) 


The NIST CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cyberseurity risks. Writing a strong incident report using CSF shows a proactive approach to protecting systems, strengthens communication with stakeholder, and helps enhance an organization's overall security posture.

Activity


Scenario


In this activity, I work as a cybersecurity analyst for a financial service company that offers online financial adviosry services and manages sensitive client information, including financail statements and personally identifiable data (PII). My organization recently experienced a Ransomeware attack that compromised the internal network and multiple employee workstations for 36-hours while the security team worked to contain the threat, restore systems, and initiate post-incident analysis.

On September 28, 2025, several employees reported being unable to access shared files on the internal server. Upon investigation, I identified that the files had been encrypted with the ".lockbit" extenstion and ransome notes were present in each affected directory demanding Bitcon payment.

Further analysis traced the initial infection to a phishing email opened by an employee. The attached Excel file contained a mailicous macro that executed a PowerShell script, which then downloaded and deployed the ransomeware payload. Within minutes, the malware spread laterally via SMB shares, encrypting data across 20 endpoints and 2 servers


To address this security event, the network securty team implemented immediate containment procedures. This included:

- Isolating infected systems from the corprate network to prevent further spread

- Disabling SMB file sharing accross affected segments

- Blocking known malicious IP addresses and command-and-control (C2) traffic at the firewall level

- Performing network segmentation to limit lateral movement
  
- Deploying endpoit scans using available antivirus and EDR tools to identify remaining traces of the malware
  
- Coordinating with IT operations to begin restoration from offline backups once the threat was contained


Task


As a cybersecurity analysis, I am tasked with using this security event to create a plan to improve my company's network security. Using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF) to help navigate through the different steps of analyzing this cybersecurity event and intergrating my analysis into general secrity strategy. 

---


Following the guideline outlined by the NIST Cybersecurity Framework:


- Identify what security risks, assests and vulnerabilities were involved

- Protect internal assets through implementation of polices, procedures, training and tools that help mitigate cybersecuirty threats

- Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.

- Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process.

- Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.
  

Incident Report Analysis

Summary 
The organization experienced a security event. All network services suddenly stopped responding compromising the internal network and multiple employee workstations. Upon further investigation the cybersecurity team discovered the disruption was a result of a ransomeware attack. The attack originated from a phishing email containing a malicious attatchment that executed a PowerShell script. The team responded by taking immediate action to contain and mitigate the threat. Their response followed by a structured appraoch aimed to limiting the spread, assessing the damage, and beginning the recovery operations.

Identify 
A malicious actor(s) targeted the company with a ransomeware attack. It took down the entire internal network. The infected assets and affected data were documented for forensic analysis and reporting

Protect
The cybersecurity team conducted a security awareness training. Even with advanced technical controls like firewalls and antivirus, employees remain the first in line of defense. We also 

Detect 

Respond 

Recover 














