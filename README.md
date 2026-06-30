# Security+ in Python

Step 3 of my [SOC Python Journey](https://github.com/dmandevv/soc-python-journey).

Studying CompTIA Security+ (SY0-701) domain by domain, and building a small Python tool for each concept to lock it in rather than just memorizing for the exam.

---

## Domains

| Domain | Exam weight | Tool | Status |
|---|---|---|---|
| 1 — General Security Concepts | 12% | [`hashing_encryption_cli.py`](hashing_encryption_cli.py) | Not started |
| 2 — Threats, Vulnerabilities & Mitigations | 22% | [`log_ioc_parser.py`](log_ioc_parser.py) | Not started |
| 3 — Security Architecture | 18% | [`firewall_rule_simulator.py`](firewall_rule_simulator.py) | Not started |
| 4 — Security Operations | 28% | [`alert_triage.py`](alert_triage.py) | Not started |
| 5 — Security Program Management & Oversight | 20% | [`access_control_simulator.py`](access_control_simulator.py) | Not started |

Each domain follows the flow in [CLAUDE.md](CLAUDE.md): explain the concept → build the tool → quiz → domain practice questions. Full timed mock exams come last, in the 1-2 weeks before test day.

---

## Roadmap

### Domain 1 — General Security Concepts
- [ ] Concept walkthrough (security controls, CIA triad/AAA, change management, cryptographic solutions)
- [ ] Build `hashing_encryption_cli.py` — hash comparison (MD5/SHA-1 vs SHA-256) + symmetric encrypt/decrypt round-trip
- [ ] Quiz
- [ ] Domain practice questions (10-20)

### Domain 2 — Threats, Vulnerabilities & Mitigations
- [ ] Concept walkthrough (threat actors, attack types, vulnerability types, mitigation techniques)
- [ ] Build `log_ioc_parser.py` — scan logs for IOCs (IPs, domains, hashes), flag against simple indicators
- [ ] Quiz
- [ ] Domain practice questions (10-20)

### Domain 3 — Security Architecture
- [ ] Concept walkthrough (architecture models, network security, infrastructure considerations, data protection)
- [ ] Build `firewall_rule_simulator.py` — evaluate traffic against an ordered allow/deny ruleset
- [ ] Quiz
- [ ] Domain practice questions (10-20)

### Domain 4 — Security Operations
- [ ] Concept walkthrough (hardening, asset management, vulnerability management, incident response, monitoring)
- [ ] Build `alert_triage.py` — ingest mock alerts, score/prioritize by severity
- [ ] Quiz
- [ ] Domain practice questions (10-20)

### Domain 5 — Security Program Management & Oversight
- [ ] Concept walkthrough (governance, risk management, compliance, audits, awareness training)
- [ ] Build `access_control_simulator.py` — RBAC-style permission checks against role definitions
- [ ] Quiz
- [ ] Domain practice questions (10-20)

### Final
- [ ] Full timed 90-question mock exam(s) (aim for 5+, per CompTIA's own pass-rate research)
- [ ] Sit the exam
