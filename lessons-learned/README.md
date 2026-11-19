# Lessons learned and next steps

- Treat unexpected requests to paste commands as untrusted; verify software provenance.
- Preserve evidence before deletion when practical, including timestamps, hashes and response transcripts.
- Separate host remediation from identity recovery: rotate credentials from a trusted device, revoke sessions, review recovery factors and payment agreements.
- For high-assurance recovery, consider reinstalling from trusted media and validate backups; absence of known IoCs does not establish complete eradication.
- Use least privilege and narrowly scoped defensive controls. Distinguish observations from inferences.
- Continue passive threat intelligence and prepare provider reports through legitimate channels. Do not directly contact suspected distribution systems.
- Validate detection rules before production use and reproduce response workflows using benign fixtures.
