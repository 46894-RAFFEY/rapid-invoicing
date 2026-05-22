# Rapid Invoicing System

Rapid Invoicing is a student-developed invoicing system that integrates with Pakistan's Federal Board of Revenue (FBR) API for invoice validation and submission. The project is presented as a practical prototype and portfolio repository. The author runs the system for a small number of clients (7) but the project has not been externally audited or certified.

Note: this repository represents a student project used in limited production. If you plan to deploy it for broader use, perform formal security reviews, backups, monitoring, and legal/compliance checks before relying on it.

![Dashboard - Example Analytics](./images/02-analytics-dashboard.png)

---

## What this repository contains

- Source for a web frontend and a backend API that demonstrate invoice creation, validation, and submission to the FBR API.
- Example screenshots and sample data for demonstration; the screenshots show client-specific or example datasets, not global usage metrics.
- Basic operational tooling and documentation to run the prototype in a small-scale environment.

---

## What it does

- Integrates with the FBR API to submit invoices and receive FBR invoice numbers
- Generates printable invoices (PDF) with QR codes
- Bulk import of invoices from Excel/CSV for faster entry
- Server-side validation and simple duplicate detection
- Lightweight role-based access control (Admin / Finance / Viewer)

---

## Screenshots

- Landing page: ./images/01-landing-page.png
- Analytics dashboard: ./images/02-analytics-dashboard.png
- Invoice creation (steps): ./images/03-create-invoice-step1-details.png, ./images/04-create-invoice-step2-buyer.png, ./images/05-create-invoice-step3-items.png
- Invoice management and history: ./images/07-invoice-management-list.png, ./images/08-submitted-invoices-history.png
- Print / PDF examples: ./images/09-invoice-print-top.png, ./images/10-invoice-print-bottom.png
- Pricing mockup: ./images/11-pricing-plans.png

Images are included as visual proof of the UI and flows; numbers shown in the screenshots are client- or demo-specific.

---

## Architecture (simplified)

```
 	React frontend  <---->  PHP backend API  <---->  MySQL database
 					|
 					+----> FBR API (invoice submission)
 					+----> Email service (SMTP)

```

This diagram intentionally shows only the components implemented in the repository. The production hosting provider may offer additional managed services (CDN, edge protection, backups) — verify with your hosting provider when deploying.

---

## Tech stack

- Frontend: React + TypeScript, Vite, Tailwind CSS
- Backend: PHP (REST API)
- Database: MySQL
- Other: Email (SMTP), QR/PDF generation libraries

---

## Usage notes

- This project is used by the maintainer with a small number of client workspaces (7). Counts shown in screenshots are example or client-specific and should not be treated as global metrics.
- The live site `rapid-invoicing.com` is the author's deployment; the code in this repository is the source used for that deployment.

---

## Security (brief)

The project includes baseline security measures implemented by the author for practical use. It has NOT undergone external certification or third-party penetration testing.

Implemented (examples):
- Token-based authentication and session handling
- Password hashing and account controls
- Server-side input validation and basic rate limiting
- Secrets stored via environment variables (no hardcoded credentials)
- Basic audit logging for important operations (e.g., invoice submission)

Limitations:
- No formal certifications (PCI, ISO, SOC, GDPR compliance statements removed)
- No external penetration testing completed
- Backups, monitoring, and advanced protections depend on the hosting provider and FBR/IRIS retention; this repository does not provide an independent enterprise backup/monitoring service

If you need to run this at scale or for regulated production environments, perform independent security assessments and implement formal monitoring, backup, and incident response practices.

---

## Documentation

- [docs/SECURITY.md](docs/SECURITY.md) — honest summary of implemented controls and limitations
- [docs/FAQ.md](docs/FAQ.md)
- [docs/TROUBLESHOOTING.md](docs/TROUBLESHOOTING.md)

---

## Roadmap (aspirational)

- Urdu language support
- Mobile app (React Native)
- Advanced analytics and reporting
- Integration with accounting software

These items are planned as future enhancements.

---

## Contact

- Email: support@rapid-invoicing.com
- Live site: https://rapid-invoicing.com

---

## License

MIT — see the LICENSE file

