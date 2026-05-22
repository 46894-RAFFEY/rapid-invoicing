## Security (practical summary)

This repository is a personal, full-stack prototype and learning project. It is not intended for production financial use.

Implemented controls (examples):
- Password hashing (e.g., PHP `password_hash`)
- Token-based authentication (JWT or similar)
- Server-side input validation
- Basic rate limiting on sensitive endpoints
- Environment variables for secrets (no credentials in source)
- Basic role separation (Admin / Finance / Viewer)
- Audit logging for important actions (invoice submission, role changes)

Limitations:
- No third-party certifications or external penetration tests have been completed.
- No managed, 24/7 monitoring or incident-response is provided by this project.
- TLS termination, backups, and other infrastructure services depend on the chosen hosting provider.
- Data residency, legal, and compliance checks are the deployer's responsibility.

Recommendations before any production use:
- Obtain an independent security assessment or penetration test.
- Configure monitored backups and a documented restore procedure.
- Use managed key management where required and rotate credentials regularly.

Report security issues to: support@rapid-invoicing.com

