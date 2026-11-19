# Cybersecurity Incident Response — Case 001

**Real-world defensive cybersecurity case study | October–November 2026**

> I did not choose to suffer a cyberattack, but I did choose how to respond.

An incident on a personal Windows workstation led to malware investigation, account compromise response and a subsequent financial fraud dispute. This repository documents the response as an independent learning project, not as employment in a SOC.

## Results and evidence boundaries

| Area | Outcome |
|---|---|
| Threat identification | Unsigned MSI and suspicious browser extension documented |
| Evidence integrity | Preserved extension archive hash and 47/47 individual file hashes matched the historical inventory |
| Containment and eradication | Performed according to the incident owner; original defensive scripts preserved |
| Post-remediation verification | Reported favorable; final execution transcripts no longer available |
| Financial recovery | Full reimbursement reported by the owner; favorable dispute resolution notice preserved |
| Threat intelligence | Distribution infrastructure documented; attribution and provider action not confirmed |

## Case files

- [Incident report and timeline](incident-report/report.md)
- [Evidence inventory and integrity](evidence/provenance.md)
- [Historical filesystem record](evidence/historical-file-list.txt)
- [Redacted indicators](indicators/iocs.json)
- [Static-analysis behavior matrix](indicators/behavior-matrix.csv)
- [Detection engineering](detection/README.md)
- [Defensive automation](defense/README.md)
- [Financial recovery](recovery/README.md)
- [Lessons learned](lessons-learned/README.md)
- [Responsible disclosure](SECURITY.md)

## Scope and authorship

The incident owner detected the problem, supplied observations, made response decisions, operated the affected system and managed account recovery and financial disputes. ChatGPT was used to support analysis, documentation and defensive script generation. This is not an institutional collaboration with OpenAI.

This publication is a retrospective, sanitized case study. No live malware, delivery commands, active download URLs or confidential account data are distributed. Static-analysis findings describe capabilities; they do not prove that every specific secret was exfiltrated. The association between the malware compromise and the later fraud is a working incident hypothesis, not a confirmed attribution.
