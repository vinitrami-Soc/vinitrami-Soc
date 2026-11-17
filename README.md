# Vinit Rami

**Cybersecurity analyst · CEH v13 · MSc Cyber Security (Merit), University of Portsmouth**

Break it like an attacker, defend it like an analyst. I spent a year running
hands-on VAPT across finance, healthcare and government, and now I bring that
attacker's instinct to detection, incident response and digital forensics.
I hold an MSc in Cyber Security and Forensic Information Technology (Merit)
from Portsmouth, where my dissertation on phishing detection became PhishHawk. I'm based in London and open to security analyst,
SOC, VAPT and DFIR roles across the UK.

[Portfolio](https://www.vinitrami.co.in) ·
[LinkedIn](https://www.linkedin.com/in/vinitrami-002855228) ·
[Medium](https://medium.com/@ramivinit) ·
[Email](mailto:ramivinit@gmail.com)

## Projects

### [PhishHawk](https://github.com/vinitrami-Soc/phishhawk)

A phishing triage engine for the SOC, built from my MSc dissertation and live
at [phishhawk.vinitrami.co.in](https://phishhawk.vinitrami.co.in). It runs the first ten minutes of L1
phishing triage by itself, from the terminal or the web app. It unwraps reported mail, catches lookalikes of your own
domain even when SPF, DKIM and DMARC pass, decodes QR codes, and sees through
Safe Links, redirects and HTML smuggling. Tested with no API keys on real mail
it had never seen, it caught 81.4% of 5,714 phishing emails, with 0.8% false
positives across 5,945 legitimate ones.

*Python · FastAPI · VirusTotal · URLScan.io · MITRE ATT&CK · STIX 2.1 · MISP*

### [IntelPulse](https://github.com/vinitrami-Soc/intelpulse)

A threat-intelligence correlation and SOC triage workbench, now a multi-user
web app. Paste an alert, raw syslog or a JSON export, or push one from a SIEM.
IntelPulse extracts the indicators, queries AbuseIPDB, OTX, GreyNoise,
ThreatFox and URLhaus at the same time, scores them into one auditable verdict,
maps how they relate, and writes a Jira-ready ticket with MITRE ATT&CK mapping.
Version 2 adds workspaces, scoped API tokens and a hash-chained audit log.

*FastAPI · async httpx · Celery + Redis · PostgreSQL · Docker* · [Live demo →](https://vinitrami-soc.github.io/intelpulse/)

### [OwlTriage](https://github.com/vinitrami-Soc/owltriage)

Offline log triage for blue teams. Point it at Linux auth and syslog, web
server logs, or Windows EVTX and Sysmon, and it says in plain sentences what
happened and what to do next. Behind that summary are 65 YAML detection rules
across 37 MITRE ATT&CK techniques, every finding with its file and line, IOCs as
NDJSON, CSV and STIX 2.1, and a firewall script to review. It also enriches
Wazuh alerts through VirusTotal and AbuseIPDB into Slack, Discord and TheHive.

*Python · YAML detection rules · Windows EVTX · Sysmon · Wazuh · STIX 2.1*

## Toolkit

- **Offensive security:** Burp Suite Pro, Metasploit, OWASP Top 10, API testing, network pentesting, privilege escalation
- **Detection and response:** SIEM, threat detection, incident response, IDS/IPS, log analysis, malware analysis
- **Digital forensics:** Autopsy, Volatility, memory and disk forensics, evidence documentation
- **Threat intel and OSINT:** VirusTotal, URLScan.io, PhishTank, OpenPhish, MXToolbox
- **Network and infrastructure:** Wireshark, Nmap, Nessus, Active Directory, AWS security
- **Code:** Python, Bash, Git

## Certifications

EC-Council Certified Ethical Hacker (CEH v13) · Digital Forensics Essentials ·
Network Defence Essentials · Ethical Hacking Essentials
