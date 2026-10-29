# Security Policy

Security matters across EllowDigital projects. Reporting privately gives maintainers a chance to investigate and mitigate an issue before technical details become public.

## Report a vulnerability privately

**Do not publish suspected vulnerabilities, exploit instructions, credentials or sensitive logs in a public issue or pull request.**

Use the repository's private vulnerability-reporting or security-advisory feature when it is enabled. Otherwise, email **ellowdigitalindia@gmail.com** with the subject **Private security report — [repository name]**.

Include, where safe:

- The affected repository, component and version or commit.
- A concise description of the potential impact.
- Reproduction steps or a minimal proof of concept that does not expose real users or data.
- Any relevant logs with secrets, tokens, personal information and private client details removed.

## Safe testing

- Do not access, modify, delete or export data belonging to other people.
- Do not perform denial-of-service testing or disruptive scans against production services.
- Do not exploit an issue beyond what is reasonably necessary to demonstrate it.
- If you discover a live credential, avoid sharing it in the report; identify its location and notify the maintainer so it can be revoked or rotated.

## What to expect

We will review reports in good faith and aim to acknowledge them as promptly as practical. Response and remediation time depends on severity, reproducibility, project ownership and available information; no fixed response-time guarantee is made.

Please allow a reasonable opportunity to investigate and address the issue before public disclosure. Do not assume that every repository has the same deployment, support window or maintenance status.

## Scope and disclosure

This policy covers security concerns relating to EllowDigital-controlled code and services. For third-party services, contact the relevant provider as well. Public visibility does not mean that a system is authorised for security testing.

If a report concerns a client-operated system, avoid testing it without explicit permission from the system owner.
