# Canadian Regulatory Compliance Plugin

A compliance assistant for Canadian multi-province operations. Covers six regulatory areas — Privacy, Employment & Labour, Financial & Securities, Health & Safety, CASL, and Tax Compliance — and helps business and operations teams understand obligations, review documents, generate checklists, draft notices, and get quick answers.

**Jurisdictions covered:** Federal, Ontario, British Columbia, Alberta, and Quebec (for privacy and tax).

---

## Commands

| Command | What it does |
|---------|-------------|
| `/compliance-review [file or description]` | Reviews a document or policy for compliance gaps across all applicable Canadian regulations. Produces a structured report with High / Medium / Low risk ratings and prioritized action items. |
| `/compliance-checklist [topic]` | Generates an actionable compliance checklist for a specific activity, regulation, or business situation. Each item includes a regulatory citation. |
| `/casl-review [message content or file]` | Reviews a draft email, SMS, or electronic campaign against CASL's three requirements (consent, identification, unsubscribe). Returns a pass/fail verdict with copy-paste fixes. |
| `/draft-notice [type + key facts]` | Drafts a regulatory notice or compliance document. Supports: PIPEDA privacy breach notifications, FINTRAC STR internal memos, OH&S workplace incident reports, ESA-compliant termination letters, CASL unsubscribe confirmations, and CASL violation response memos. |
| `/compliance-qa [your question]` | Answers a compliance question in plain language with a direct answer, regulatory explanation, jurisdiction comparison, and practical guidance. |

### Example Usage

```
/compliance-review privacy-policy.pdf
/compliance-checklist onboarding a new remote employee in Ontario
/casl-review [paste email draft here]
/draft-notice PIPEDA breach — 1,200 customer email addresses exposed in phishing attack
/draft-notice CASL unsubscribe confirmation for john@example.com
/compliance-qa Do we need to register for GST if our revenue is $28,000?
/compliance-qa Can we send marketing emails to a list we purchased?
```

---

## Skills

The plugin loads specialized regulatory knowledge automatically when you discuss relevant topics:

| Skill | Activates when you ask about |
|-------|----------------------------|
| Canadian Privacy Compliance | PIPEDA, Bill C-27, personal information, privacy policies, data breaches, consent |
| Canadian Employment & Labour | Employment standards, termination, notice periods, human rights, leave, minimum wage |
| Canadian Financial & Securities | FINTRAC, AML, KYC, LCTR, STR, OSC, CIRO, securities filings |
| Canadian Health & Safety | WHMIS, OH&S, workplace incidents, SDS, right to refuse, CCOHS |
| CASL Compliance | Anti-spam, commercial electronic messages, email/SMS marketing, opt-in, unsubscribe |
| Canadian Tax Compliance | GST/HST, PST/QST, payroll, CPP/EI, T4/T4A, corporate tax, SR&ED, contractor vs employee |

---

## Changelog

### v0.2.0
- Added CASL (Canada's Anti-Spam Legislation) skill with consent decision tree and campaign review rubric
- Added Canadian Tax Compliance skill covering GST/HST, payroll, corporate tax, and SR&ED
- Added `/casl-review` command for email/SMS campaign compliance review
- Updated `/draft-notice` to support CASL unsubscribe confirmations and violation response memos

### v0.1.0
- Initial release with Privacy, Employment, Financial/Securities, and Health & Safety coverage

---

## Important Disclaimer

This plugin provides general regulatory information for educational purposes. It is **not legal or tax advice**. Canadian regulatory requirements are complex, change frequently, and depend heavily on your specific circumstances. Always consult a qualified lawyer, accountant, or compliance professional before making compliance decisions.

---

## Setup

No environment variables or external service connections required. The plugin is fully self-contained.

---

## Author

Srivatsa Kasagar — v0.2.0
