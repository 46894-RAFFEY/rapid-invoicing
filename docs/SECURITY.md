## Security & Compliance (concise, honest summary)

This document describes the baseline security measures implemented in this repository and clearly states known limitations. The project is a student-developed prototype that the author runs for a small number of clients; it has not been externally certified or penetration-tested.

Last updated: 2026-05-22

### Implemented (summary)
- Token-based authentication and session handling
- Password hashing and account controls
- Server-side input validation and basic rate limiting
- Secrets managed via environment variables (no hardcoded credentials in source)
- Basic audit logging for key operations (for example: invoice submission history)

### Limitations (please read)
- No third-party certifications (PCI DSS, ISO 27001, SOC 2, GDPR certification, etc.) are provided by this project.
- No external penetration tests or formal third-party security audits have been completed for this repository.
- The project does not provide a managed, 24/7 monitoring/incident-response service.
- Backups, edge/CDN protection and other infrastructure-level services depend on the hosting provider and FBR/IRIS systems; this repository does not itself guarantee those services.

### Guidance before broader production use
If you plan to deploy for wider or regulated production use, perform the following independent steps:
- Commission an external penetration test and vulnerability assessment
- Implement formal monitoring and alerting (host and application level)
- Establish an independent backup and restore strategy and test restores regularly
- Verify data residency and legal/compliance requirements for your customers
- Use managed key management and rotate keys as required by your compliance needs

### Reporting issues
Report security issues to: support@rapid-invoicing.com

This document intentionally avoids operational claims that are not implemented in this repository. If you need assistance hardening or certifying a deployment, I can outline next steps and a checklist.

