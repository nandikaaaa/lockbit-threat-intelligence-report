# lockbit-threat-intelligence-report
Threat Intelligence Report analysing LockBit ransomware using MITRE ATT&amp;CK techniques, Indicators of Compromise (IOCs), attack lifecycle and mitigation strategies.
📌 Overview

This project presents a structured threat intelligence analysis of the LockBit Ransomware-as-a-Service (RaaS) operation. It examines adversary tactics, techniques, and procedures (TTPs), maps behavior to the MITRE ATT&CK framework, and identifies detection and mitigation opportunities from a SOC analyst perspective.

The analysis is based on open-source intelligence including CISA/FBI advisories, Microsoft Threat Intelligence reports, MITRE ATT&CK framework, and Unit 42 research.

🎯 Objectives
Analyze LockBit ransomware attack lifecycle end-to-end
Map adversary behavior to MITRE ATT&CK v13.1
Identify Indicators of Compromise (IOCs) and behavioral patterns
Highlight detection opportunities in a SOC environment
Provide defensive recommendations for enterprise security teams
🧠 Key Findings
LockBit relies heavily on living-off-the-land tools (RDP, PsExec, PowerShell, AnyDesk)
Data exfiltration typically occurs before encryption, creating a short detection window
Affiliate-driven model leads to high variability in attack techniques
Effective defense requires behavioral detection, not signature-based rules
Known vulnerabilities remain a primary initial access vector
🧩 Techniques & Frameworks Used
MITRE ATT&CK Enterprise Framework (v13.1)
CISA & FBI Joint Advisories
Microsoft Defender Threat Intelligence
Palo Alto Networks Unit 42 Reports
📊 Contents
Full ransomware attack lifecycle analysis
MITRE ATT&CK mapping table
Indicators of Compromise (network, host, behavioral)
Detection engineering opportunities
Mitigation strategies aligned with SOC best practices
