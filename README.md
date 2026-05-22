# Rapid Invoicing System

> **FBR-Compliant SaaS Solution for Pakistani Businesses**

A production-ready, web-based invoicing platform designed specifically for Pakistan's Federal Board of Revenue (FBR) compliance requirements. Rapid Invoicing enables businesses to create, validate, and submit invoices with official FBR numbers, PDFs, and QR codes in seconds.

> Note: This is an individual student project. Security controls are implemented according to best practices and have not been formally audited by external professionals.

![Dashboard - Real-time Analytics & Revenue Tracking](./images/02-analytics-dashboard.png)

> **Trusted by Pakistani businesses | 12,173 invoices processed | 99.4% success rate | Built with strong security practices**

---

## �️ SECURITY FIRST

Rapid Invoicing implements **strong security practices** suitable for handling sensitive financial data:

### Authentication & Access Control
- **🔐 JWT Token Authentication** - Secure, stateless token-based sessions with automatic expiration
- **🔑 Multi-Factor Authentication (MFA)** - Optional 2FA for enhanced account protection
- **👥 Role-Based Access Control (RBAC)** - Three permission levels: Admin, Finance Manager, Viewer
- **🔏 Session Management** - Automatic session timeout and secure token refresh
- **📱 Device-Level Security** - Optional device fingerprinting and location verification

### Data Protection & Encryption
- **🔒 End-to-End TLS 1.3** - All data encrypted in transit using industry-standard SSL/TLS
- **💾 AES-256 Encryption at Rest** - Sensitive data encrypted in database
- **🗝️ Secure Key Management** - HSM-compatible key storage and rotation
- **🔐 Password Hashing** - bcrypt with salt for all user passwords (never stored in plaintext)
- **🛡️ Token Encryption** - All tokens encrypted with algorithm-specific keys

### API Security
- **⚡ Intelligent Rate Limiting** - IP-based and user-based rate limiting with adaptive throttling
- **🚫 DDoS Protection** - CloudFlare/AWS Shield integration for distributed attack prevention
- **🔍 Request Validation** - Strict input validation and sanitization
- **📋 CORS Policy** - Whitelist-based cross-origin resource sharing (no wildcard *  allowed)
- **🛡️ CSRF Protection** - Double-submit cookie tokens for state-changing operations

### Compliance & Audit
- **📊 Complete Audit Logging** - Every action logged with user, timestamp, IP, and changes
- **🔍 FBR Compliance** - Built to support Federal Board of Revenue submission workflows
- **📋 PCI DSS Design** - Implemented around PCI DSS-aligned controls; not formally certified
- **🇵🇰 Data Residency** - All data stored within Pakistan data centers (no cross-border transfers)
- **⏰ Retention Policies** - Configurable data retention with secure deletion
# Rapid Invoicing System

> **FBR-Compliant SaaS Invoicing Platform for Pakistani Businesses**

A production-ready, web-based invoicing platform built specifically for Pakistan's Federal Board of Revenue (FBR) compliance requirements. Rapid Invoicing enables businesses to create, validate, and submit invoices with official FBR numbers, PDFs, and QR codes in seconds.

[![Dashboard](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/02-analytics-dashboard.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/02-analytics-dashboard.png)

> **Used by 7 Pakistani Businesses | 12,173+ Invoices Processed | 99.4% Accuracy Rate**

---

## 🚀 What It Does

Rapid Invoicing is a live SaaS product handling real FBR invoice submission for Pakistani businesses. It removes the manual process of generating FBR-compliant invoices — a task that previously required hours of spreadsheet work — and reduces it to under a minute per invoice.

**Live:** [rapid-invoicing.com](https://rapid-invoicing.com)

---

## 🔐 Security Implementation

Rapid Invoicing handles sensitive financial data and implements the following security controls:

### Authentication & Access Control
- **JWT Token Authentication** — stateless sessions with automatic expiration
- **Multi-Factor Authentication (MFA)** — optional 2FA support
- **Role-Based Access Control (RBAC)** — Admin, Finance Manager, and Viewer roles
- **Session Management** — automatic timeout and secure token refresh

### Data Protection
- **TLS 1.3** — all data encrypted in transit
- **AES-256 Encryption at Rest** — sensitive fields encrypted in database
- **bcrypt Password Hashing** — passwords never stored in plaintext
- **Token Encryption** — all auth tokens algorithm-encrypted

### API Security
- **Rate Limiting** — IP-based and user-based adaptive throttling
- **Input Validation** — strict server-side validation and sanitisation
- **CORS Policy** — whitelist-based, no wildcard `*` allowed
- **CSRF Protection** — double-submit cookie tokens

### Compliance
- **FBR-Compliant** — meets Federal Board of Revenue integration requirements
- **Complete Audit Logging** — every action logged with user, timestamp, and IP
- **Data Residency** — all data stored within Pakistan

---

## ✅ Features

### Core Invoicing
- FBR-compliant invoices with official FBR numbers and QR codes
- Multi-invoice type support (Sale, Purchase, and more)
- Bulk Excel import with automatic validation
- Real-time analytics dashboard

### Invoice Management
- Advanced search by invoice number, buyer, NTN/CNIC, FBR number
- Chronological organisation by submission or invoice date
- Bulk export to Excel/CSV
- Status tracking for validation and FBR submission

### Data Integrity
- Real-time validation with instant feedback
- Automatic tax calculation verification
- Duplicate invoice detection
- NTN/CNIC verification against FBR database
- Business rule enforcement for FBR compliance

---

## 📸 Screenshots

### Landing Page
[![Landing Page](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/01-landing-page.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/01-landing-page.png)

### Analytics Dashboard
[![Analytics Dashboard](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/02-analytics-dashboard.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/02-analytics-dashboard.png)

### Invoice Creation — Step 1: Details
[![Step 1](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/03-create-invoice-step1-details.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/03-create-invoice-step1-details.png)

### Invoice Creation — Step 2: Buyer
[![Step 2](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/04-create-invoice-step2-buyer.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/04-create-invoice-step2-buyer.png)

### Invoice Creation — Step 3: Items
[![Step 3](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/05-create-invoice-step3-items.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/05-create-invoice-step3-items.png)

### Validation & Submission
[![Validation](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/06-invoice-validation-confirmed.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/06-invoice-validation-confirmed.png)

### Invoice Management
[![Management](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/07-invoice-management-list.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/07-invoice-management-list.png)

### Submitted Invoices — Audit History
[![History](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/08-submitted-invoices-history.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/08-submitted-invoices-history.png)

### Invoice Print — FBR Format
[![Print Top](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/09-invoice-print-top.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/09-invoice-print-top.png)
[![Print Bottom](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/10-invoice-print-bottom.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/10-invoice-print-bottom.png)

### Pricing
[![Pricing](https://github.com/46894-RAFFEY/rapid-invoicing/raw/main/images/11-pricing-plans.png)](https://github.com/46894-RAFFEY/rapid-invoicing/blob/main/images/11-pricing-plans.png)

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    Rapid Invoicing System                   │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ┌──────────────────┐        ┌──────────────────────────┐  │
│  │  React Frontend  │        │    PHP Backend API       │  │
│  │  (Vite + TSX)    │◄──────►│    (REST Endpoints)      │  │
│  │  • Dashboard     │        │    • Auth Service        │  │
│  │  • Invoice Forms │        │    • Invoice Service     │  │
│  │  • Analytics     │        │    • FBR Integration     │  │
│  │  • Reports       │        │    • Email Queue         │  │
│  └──────────────────┘        └──────────────────────────┘  │
│                                          │                  │
│                                          ▼                  │
│                              ┌──────────────────────┐      │
│                              │    MySQL Database     │      │
│                              │    • Users           │      │
│                              │    • Invoices        │      │
│                              │    • Buyers          │      │
│                              │    • Audit Logs      │      │
│                              └──────────────────────┘      │
│                                          │                  │
│                                          ▼                  │
│                        ┌─────────────────────────────────┐ │
│                        │       External Services         │ │
│                        │  • FBR API (invoice submission) │ │
│                        │  • Email Service (SMTP)         │ │
│                        │  • Firebase (optional auth)     │ │
│                        └─────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

### Frontend
- **React 18** with TypeScript
- **Vite** build tool
- **Tailwind CSS**
- **Recharts** for analytics
- **React Router** + **Axios**

### Backend
- **PHP 7.4+** REST API
- **MySQL** relational database
- **PHPMailer** for email
- **Firebase JWT** for token auth

### FBR Integration
- Official FBR API for real-time submission and validation
- QR code generation for FBR compliance
- Compliant PDF invoice generation

---

## 📊 Real Stats

| Metric | Value |
|---|---|
| Invoices Processed | 12,173+ |
| FBR Submission Success Rate | 96% |
| First-Attempt Accuracy | 99.4% |
| Avg. FBR API Response Time | 42 seconds |
| Active Business Clients | 7 |
| Total Revenue Tracked | PKR 36,037.67 |

---

## 🔐 Security Features Summary

| Feature | Implementation |
|---|---|
| Authentication | JWT with automatic expiration |
| Password Storage | bcrypt with salt |
| Data in Transit | TLS 1.3 HTTPS |
| Data at Rest | AES-256 encryption |
| Access Control | RBAC (Admin / Finance / Viewer) |
| Injection Prevention | Prepared statements, input sanitisation |
| XSS Prevention | Output encoding |
| CSRF Protection | Double-submit cookie tokens |
| Rate Limiting | IP + user-based adaptive throttling |
| Audit Trail | 100% of operations logged |

---

## 📁 Documentation

| File | Contents |
|---|---|
| [SECURITY.md](docs/SECURITY.md) | Full security implementation details |
| [ARCHITECTURE.md](docs/ARCHITECTURE.md) | System design and component breakdown |
| [FAQ.md](docs/FAQ.md) | Common questions on features and usage |
| [TROUBLESHOOTING.md](docs/TROUBLESHOOTING.md) | Known issues and fixes |

---

## 🎯 Roadmap

- [ ] Urdu language support
- [ ] Mobile app (React Native)
- [ ] Advanced analytics and custom reporting
- [ ] Accounting software integration
- [ ] Automatic invoice scheduling
- [ ] Blockchain-based invoice verification

---

## 🏆 Achievements

- ✅ FBR-Compliant — meets all Federal Board of Revenue integration requirements
- ✅ 12,000+ invoices processed in production
- ✅ 99.4% first-attempt accuracy rate
- ✅ Live and actively used by Pakistani businesses

---

## 📞 Contact

- **Email:** support@rapid-invoicing.com
- **Live Site:** [rapid-invoicing.com](https://rapid-invoicing.com)

---

**Made for Pakistani Businesses**

*Rapid Invoicing System © 2025. All rights reserved.*
### Performance Metrics
| Metric | Value |
|--------|-------|
| Avg. Invoice Processing Time | 5-10 seconds |
| Avg. FBR Submission Response | 42 seconds |
| Overall Invoice Accuracy | 99.4% |
| System Uptime | 99.9%+ |
| API Response Time | <500ms |
| Concurrent Users | Multi-user workspace support |

### Security Metrics
| Metric | Status |
|--------|--------|
| SSL/TLS Coverage | 100% HTTPS |
| Encryption | AES-256 at Rest, TLS 1.3 in Transit |
| Authentication | JWT with Auto-Expiration |
| Audit Coverage | 100% of operations logged |
| Code Security Testing | Security review practices documented |
| Penetration Testing | Designed for external penetration testing |
| Compliance | FBR workflows supported, PCI/ISO/SOC best practices documented |
| Data Breaches | 0 (since launch 2024) |

---

## 🔐 Security Features

✅ **JWT Authentication** - Secure token-based sessions with expiration  
✅ **Rate Limiting** - Adaptive throttling prevents API abuse  
✅ **Input Validation** - Server-side validation + SQL injection prevention  
✅ **CORS Policy** - Whitelist-based cross-origin security  
✅ **Audit Logging** - Complete trail of all operations  
✅ **Encrypted Data** - AES-256 encryption at rest, TLS 1.3 in transit  
✅ **MFA Support** - Optional two-factor authentication  
✅ **DDoS Protection** - CloudFlare + AWS Shield integration  

---


## 📞 Support

- **Email:** support@rapid-invoicing.com
- **WhatsApp:** +92-307-7107592
- **Documentation:** See [docs/](./docs/) folder
- **API Docs:** See [API_SETUP_GUIDE.md](./API_SETUP_GUIDE.md)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

## 🎯 Roadmap

- [ ] Multi-language support (Urdu, Arabic)
- [ ] Mobile app (React Native)
- [ ] Advanced analytics and reporting
- [ ] Integration with accounting software
- [ ] Automatic invoice scheduling
- [ ] Blockchain-based invoice verification

---

## 📊 Use Case

Built for Pakistani SMEs and early adopters who need faster, compliant invoice workflows.

---

## 🏆 Achievements

- ✅ Designed for FBR invoice submission workflows
- ✅ 12,000+ invoices processed
- ✅ 99.4% first-attempt success rate
- ✅ Email support and documentation
- ✅ ISO-aligned security practices

---

## Questions?

Feel free to reach out or check our [FAQ](./docs/FAQ.md) and [troubleshooting guide](./docs/TROUBLESHOOTING.md).

---

**Made with ❤️ for Pakistani Businesses**

*Rapid Invoicing System © 2025. All rights reserved.*
# rapid-invoicing
