# Canadian Regulatory Compliance Plugin

A compliance assistant for Canadian multi-province operations. Covers nine regulatory areas — Privacy, Employment & Labour, Financial & Securities, Health & Safety, CASL, Tax Compliance, Immigration & Work Permits, Environmental Compliance, and Corporate Governance — and helps business and operations teams understand obligations, review documents, generate checklists, draft notices, and get quick answers.

**Jurisdictions covered:** Federal, Ontario, British Columbia, Alberta, and Quebec (for privacy and tax).

---

## Commands

| Command | What it does |
|---------|-------------|
| `/compliance-review [file or description]` | Reviews a document or policy for compliance gaps across all applicable Canadian regulations. Produces a structured report with High / Medium / Low risk ratings and prioritized action items. |
| `/compliance-checklist [topic]` | Generates an actionable compliance checklist for a specific activity, regulation, or business situation. Each item includes a regulatory citation. |
| `/casl-review [message content or file]` | Reviews a draft email, SMS, or electronic campaign against CASL's three requirements (consent, identification, unsubscribe). Returns a pass/fail verdict with copy-paste fixes. |
| `/draft-notice [type + key facts]` | Drafts a regulatory notice or compliance document. Supports 8 notice types — see full list below. |
| `/compliance-qa [your question]` | Answers a compliance question in plain language with a direct answer, regulatory explanation, jurisdiction comparison, and practical guidance. |

### /draft-notice — Supported Types

| Type | Use case |
|------|---------|
| A. PIPEDA Privacy Breach | Notify OPC + affected individuals of a data breach |
| B. FINTRAC STR Memo | Internal documentation for a suspicious transaction report |
| C. OH&S Incident Report | Workplace injury/near-miss report for provincial regulators |
| D. ESA Termination Letter | ESA-compliant termination letter (ON, BC, AB, or Federal) |
| E. CASL Unsubscribe Confirmation | Confirm removal from mailing list after unsubscribe request |
| F. CASL Violation Response | Internal memo / CRTC inquiry response for CASL complaint |
| G. LMIA Employer Support Letter | Employer letter supporting an LMIA application to ESDC |
| H. ESDC Compliance Response | Response to an ESDC TFWP compliance inspection or inquiry |

### Example Usage

```
/compliance-review privacy-policy.pdf
/compliance-checklist onboarding a new remote employee in Ontario
/casl-review [paste email draft here]
/compliance-qa Do we need an LMIA to hire a US engineer under CUSMA?
/compliance-qa What is the carbon price for our Alberta facility in 2024?
/compliance-qa What records must be in our corporate minute book?
/draft-notice LMIA support letter — Software Engineer, NOC 21232, $120,000/year, Toronto
/draft-notice ESDC compliance inspection response — payroll records for 2 TFWs
```

---

## Skills

The plugin loads specialized regulatory knowledge automatically when relevant topics come up:

| Skill | Activates when you ask about |
|-------|----------------------------|
| Canadian Privacy Compliance | PIPEDA, Bill C-27, personal information, privacy policies, data breaches, consent |
| Canadian Employment & Labour | Employment standards, termination, notice periods, human rights, leave, minimum wage |
| Canadian Financial & Securities | FINTRAC, AML, KYC, LCTR, STR, OSC, CIRO, securities filings |
| Canadian Health & Safety | WHMIS, OH&S, workplace incidents, SDS, right to refuse, CCOHS |
| CASL Compliance | Anti-spam, commercial electronic messages, email/SMS marketing, opt-in, unsubscribe |
| Canadian Tax Compliance | GST/HST, PST/QST, payroll, CPP/EI, T4/T4A, corporate tax, SR&ED, contractor vs employee |
| Canadian Immigration | LMIA, work permits, Express Entry, PNP, CUSMA, IMP, employer compliance, IRCC |
| Canadian Environmental | CEPA, carbon pricing, OBPS, BC carbon tax, Alberta TIER, hazardous waste, EA triggers |
| Canadian Corporate Governance | CBCA, director duties, annual filings, minute book, ISC register, shareholder rights |

---

## Changelog

### v0.3.0
- Added Canadian Immigration & Work Permits skill (LMIA, IMP, CUSMA, Express Entry, PNPs, employer compliance)
- Added Canadian Environmental Compliance skill (CEPA, carbon pricing, OBPS, TIER, BC carbon tax, hazardous waste, EA triggers)
- Added CBCA / Corporate Governance skill (director duties, annual filings, ISC register, shareholder rights)
- Updated `/draft-notice` with LMIA employer support letter and ESDC compliance response templates

### v0.2.0
- Added CASL skill and `/casl-review` command
- Added Canadian Tax Compliance skill
- Updated `/draft-notice` with CASL templates

### v0.1.0
- Initial release: Privacy, Employment, Financial/Securities, Health & Safety

---

## Important Disclaimer

This plugin provides general regulatory information for educational purposes. It is **not legal, tax, or immigration advice**. Canadian regulatory requirements are complex, change frequently, and depend heavily on your specific circumstances. Always consult a qualified lawyer, accountant, or regulated immigration consultant (RCIC) before making compliance decisions.

---

## Setup

No environment variables or external service connections required. The plugin is fully self-contained.

---

## Author

Srivatsa Kasagar — v0.3.0
