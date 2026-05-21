# Frequently Asked Questions

## General Questions

### What is Rapid Invoicing?

Rapid Invoicing is a SaaS platform specifically designed for Pakistani businesses to create, validate, and submit FBR-compliant invoices. It automates the invoice generation process and integrates directly with FBR's system.

### How does it work?

1. Create an invoice with buyer and item details
2. System validates against FBR requirements
3. Submit to FBR for official approval
4. Receive FBR number, PDF, and QR code
5. Track and manage all invoices in one dashboard

### Is it FBR compliant?

Yes, Rapid Invoicing is fully FBR-compliant and certified. All invoices are validated against FBR requirements before submission.

### How much does it cost?

See our pricing plans at [https://rapid-invoicing.com/pricing](https://rapid-invoicing.com/pricing)

### Do you offer a free trial?

Yes! Sign up at [https://rapid-invoicing.com](https://rapid-invoicing.com) for a 30-day free trial.

---

## Technical Questions

### What browsers are supported?

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

### How secure is my data?

We use industry-standard security:
- JWT token authentication
- SSL/TLS encryption
- Rate limiting and DDoS protection
- Security review practices
- Complete audit logging
- ISO-aligned practices

### Can I import invoices from Excel?

Yes! Use the Import feature to upload bulk invoices from Excel files.

### What file formats can I export?

- Excel (.xlsx)
- CSV (.csv)
- PDF (individual invoices)

### Does it work offline?

The web application requires internet connection. However, you can save invoices as drafts and submit later when online.

---

## Account & Access

### How do I create an account?

1. Visit [https://rapid-invoicing.com](https://rapid-invoicing.com)
2. Click "Sign Up"
3. Enter your business details
4. Verify your email
5. Set up your workspace

### Can multiple users access one account?

Yes! Rapid Invoicing supports multi-user workspaces with role-based access control:
- **Admin** - Full access including user management
- **Finance Manager** - Create and submit invoices
- **Viewer** - Read-only access to reports

### How do I reset my password?

1. Go to login page
2. Click "Forgot Password?"
3. Enter your email
4. Click the reset link in your email
5. Enter your new password

### How do I change my plan?

Log in to your account and go to Settings > Billing > Change Plan.

---

## Invoicing

### What types of invoices can I create?

- Sale Invoices
- Purchase Invoices (if enabled by FBR)
- Other types as per FBR regulations

### How long does FBR validation take?

Average validation takes 42 seconds, but can vary from 15 seconds to 5 minutes depending on FBR system load.

### Why did my invoice fail validation?

Common reasons:
1. Invalid NTN/CNIC format
2. Buyer not registered with FBR
3. Missing required fields
4. Tax calculation mismatch
5. Duplicate invoice number

Check the error message for specific details.

### Can I edit an invoice after submission?

No, once submitted to FBR, the invoice cannot be edited. However, you can create a reversal invoice if needed.

### How do I reverse an invoice?

Contact our support team. We'll help you create a reversal entry.

---

## FBR Integration

### How is FBR integration different from manual submission?

Rapid Invoicing automates the entire process:
- Automatic FBR validation
- Real-time FBR submission
- Automatic QR code and PDF generation
- Official FBR receipt

Manual submission would require going through FBR portal for each invoice.

### What FBR data do you have access to?

We only access:
- Buyer NTN/CNIC verification
- Seller information validation
- FBR invoice number generation

We do NOT store or access sensitive FBR credentials.

### How often is FBR data updated?

FBR validation happens in real-time. NTN/CNIC databases are updated as FBR updates them.

---

## Billing & Payments

### What payment methods do you accept?

- Credit/Debit cards (Visa, Mastercard)
- Bank transfer (for enterprise)
- Mobile payments (Jazz Cash, Easypaisa for Pakistan)

### Do you offer refunds?

Yes, we offer a 14-day money-back guarantee for annual plans.

### Is there a setup fee?

No setup fees. You only pay for the plan you choose.

### Do you offer enterprise pricing?

Yes! For high-volume users (5000+ invoices/month), contact sales@rapid-invoicing.com for custom pricing.

---

## Support & Troubleshooting

### How do I contact support?

- **Email:** support@rapid-invoicing.com
- **WhatsApp:** +92-XXX-XXXXXXX
- **In-App Chat:** Available 9 AM - 5 PM (PKT)

### What's your response time?

- Priority (Premium plans): 1-2 hours
- Standard (Free plans): 24 hours

### Where can I see my invoices?

Log in to your account and go to "Invoice List" or "Submitted Invoices".

### How do I export my data?

Go to Settings > Data Export to download all your data in Excel format.

---

## API Questions

### Do you provide an API?

Yes! Rapid Invoicing provides a complete REST API for developers. See [API Documentation](../API_SETUP_GUIDE.md).

### How do I get API credentials?

1. Log in to your account
2. Go to Settings > API
3. Generate an API key
4. Use the key for API authentication

### What's the API rate limit?

- Free plan: 100 requests/hour
- Professional plan: 1,000 requests/hour
- Enterprise: Custom limits

### Can I integrate with my accounting software?

Yes! We provide integrations with:
- QuickBooks
- Xero
- SAGE
- And custom API integration

---

## Data & Privacy

### Where is my data stored?

Your data is stored in secure data centers located in Pakistan with regular backups.

### How long do you retain my data?

We retain your data as long as your account is active. After account deletion, data is purged within 30 days.

### Is my data encrypted?

Yes, all data is encrypted:
- In transit: SSL/TLS
- At rest: AES-256 encryption

### Can I export all my data?

Yes, go to Settings > Data Export to download all your invoices and data.

---

Still have questions? Contact us at support@rapid-invoicing.com
