# Frequently Asked Questions

## General Questions

### What is Rapid Invoicing?

Rapid Invoicing is a student-developed invoicing prototype that demonstrates integration with the Federal Board of Revenue (FBR) API for invoice validation and submission.

### How does it work?

1. Create an invoice with buyer and item details
2. Server-side validation runs against configured business rules
3. The system can submit invoices to the FBR API for official processing
4. When accepted, an FBR invoice number and PDF/QR are returned
5. Track and manage invoices via the dashboard

### Is it FBR "certified"?

The project integrates with the FBR API for submission and validation, but the repository and software are not certified by any external body. If you deploy this software, verify FBR registration and any local legal or regulatory requirements.

### How much does it cost?

Pricing on the demo site is illustrative and for demonstration only.

---

## Technical Questions

### What browsers are supported?

- Chrome/Edge (modern versions)
- Firefox (modern versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

### How secure is my data?

The project includes baseline security measures implemented by the author (authentication, password handling, input validation, and basic rate limiting). This repository has not undergone third-party audits or penetration testing. If you plan to deploy beyond demonstration use, perform an independent security review.

### Can I import invoices from Excel?

Yes — the import feature accepts Excel/CSV files and performs server-side validation.

### What file formats can I export?

- Excel (.xlsx)
- CSV (.csv)
- PDF (individual invoices)

### Does it work offline?

The web application requires an internet connection for FBR submission. Drafts can be saved locally and submitted when online.

---

## Account & Access

### How do I create an account?

To try the signup flow, use the demo site and verify your email.

### Can multiple users access one account?

The prototype includes support for multi-user workspaces with role-based permissions.

### How do I reset my password?

Use the "Forgot Password" link on the login page.

---

## Invoicing

### What types of invoices can I create?

- Sale and purchase invoices (as supported by FBR workflows)

### How long does FBR validation take?

Validation time depends on the FBR system; examples in screenshots are client-specific and may not reflect all conditions.

### Why did my invoice fail validation?

Common reasons include invalid identifiers, missing required fields, tax calculation issues, or duplicate invoice numbers. Check the error details in the UI.

### Can I edit an invoice after submission?

Invoices submitted to FBR generally cannot be edited; follow local procedures for corrections or reversals.

---

## FBR Integration

### How is FBR integration different from manual submission?

The system automates validation and submission to the FBR API where available; manual submission via the FBR portal is separate and has its own rules.

### What FBR data do you have access to?

Typically: buyer/seller verification and invoice submission/response records. The software does not store FBR credentials in source code.

---

## Support & Troubleshooting

### How do I contact support?

- Email: support@rapid-invoicing.com

### What's your response time?

Contact support@rapid-invoicing.com; response times vary.

---

## API Questions

### Do you provide an API?

Yes. See the API documentation in the repository for endpoints and authentication details.

### How do I get API credentials?

In a deployed instance, administrators can generate API credentials through account settings.

---

## Data & Privacy

### Where is my data stored?

Data location depends on the hosting provider used for a deployment. Verify data residency and backup policies with the deployment host.

### Is my data encrypted?

Encryption is used in the application for data in transit and at rest where supported by the deployment. Specific algorithms and configurations depend on how the application is deployed and hosted.

---

Still have questions? Contact support@rapid-invoicing.com
