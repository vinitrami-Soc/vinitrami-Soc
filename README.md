# Vinit Rami

**Cybersecurity analyst · CEH v13 · MSc Cyber Security, University of Portsmouth**

Break it like an attacker, defend it like an analyst. I spent a year running
hands-on VAPT across finance, healthcare and government, and now I bring that
attacker's instinct to detection, incident response and digital forensics.
I've just finished my MSc at Portsmouth, where my dissertation on phishing
detection became PhishHawk. I'm based in London and open to security analyst,
SOC, VAPT and DFIR roles across the UK.

[Portfolio](https://vinitrami-soc.github.io) ·
[LinkedIn](https://www.linkedin.com/in/vinitrami-002855228) ·
[Medium](https://medium.com/@ramivinit) ·
[Email](mailto:ramivinit@gmail.com)

## Projects

### [PhishHawk](https://github.com/vinitrami-Soc/phishhawk)

A phishing triage engine for the SOC, built from my MSc dissertation. It runs
the first ten minutes of L1 phishing triage by itself, from the terminal or a
self-hosted web app. It unwraps reported mail, catches lookalikes of your own
domain even when SPF, DKIM and DMARC pass, decodes QR codes, and sees through
Safe Links, redirects and HTML smuggling. Tested with no API keys on real mail
it had never seen, it caught 81.3% of 5,714 phishing emails, with 0.8% false
positives across 5,945 legitimate ones.

*Python · FastAPI · VirusTotal · URLScan.io · MITRE ATT&CK · STIX 2.1 · MISP*

### [IntelPulse](https://github.com/vinitrami-Soc/intelpulse)

A threat-intelligence correlation and SOC triage workbench. Paste an alert, raw syslog or a JSON export. IntelPulse extracts the indicators,
queries AbuseIPDB, OTX, GreyNoise, ThreatFox and URLhaus at the same time,
scores them into one auditable verdict, maps how they relate, and writes a
Jira-ready ticket with MITRE ATT&CK mapping.

*FastAPI · async httpx · Celery + Redis · PostgreSQL · Docker* · [Live demo →](https://vinitrami-soc.github.io/intelpulse/)

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
