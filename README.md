# PhishGuard — Customer Message & Link Verification Portal

An IT Security advisory and message inspection tool designed to help customers recognize convincing scams and phishing messages arriving via **Email** or **WhatsApp**.

## Live Demo & GitHub Pages
When deployed via GitHub Pages, this repository serves `index.html` as an interactive zero-dependency web app.

## Features
1. **Scam & Phishing Analyzer**:
   - Presets for convincing WhatsApp & Email attacks (Bank freeze .APK traps, lookalike M365 invoices, customs parcel fees, HR payroll urgency).
   - Scans for urgency manipulation, typosquatted lookalike domains, obfuscated URL shorteners, and dangerous executable/sideload payloads.
2. **Safe Verification Checklist**:
   - Out-of-band verification steps tailored to the message channel (Email vs. WhatsApp).
3. **Mandatory Post-Check Hard Lock**:
   - Once checked, the primary proceed action is disabled (**Unable to Proceed**).
4. **Secondary Own-Risk Disclaimer Modal**:
   - If a customer insists on proceeding, a disclaimer pop-up requires risk acknowledgment and a stated justification before proceeding strictly at their own risk.
5. **Central Action Log & Audit Dashboard**:
   - Tracks all scans, automated blocks, disclaimer views, cancellations, and risk overrides with KPI metrics, filters, and CSV export.
6. **System Blueprint**:
   - Built-in visual architecture diagram illustrating the customer protection flow.
