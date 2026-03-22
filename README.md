# Canadian Regulatory Compliance Plugin

A compliance assistant for Canadian multi-province operations. Covers four regulatory areas — Privacy, Employment & Labour, Financial & Securities, and Health & Safety — and helps business and operations teams understand obligations, review documents, generate checklists, draft notices, and get quick answers.

**Jurisdictions covered:** Federal, Ontario, British Columbia, Alberta, and Quebec (for privacy).

---

## Commands

| Command | What it does |
|---------|-------------|
| `/compliance-review [file or description]` | Reviews a document or policy for compliance gaps across all applicable Canadian regulations. Produces a structured report with High / Medium / Low risk ratings and prioritized action items. |
| `/compliance-checklist [topic]` | Generates an actionable compliance checklist for a specific activity, regulation, or business situation. Each item includes a regulatory citation. |
| `/draft-notice [type + key facts]` | Drafts a regulatory notice or compliance document. Supports: PIPEDA privacy breach notifications, FINTRAC STR internal memos, OH&S workplace incident reports, and ESA-compliant termination letters. |
| `/compliance-qa [your question]` | Answers a compliance question in plain language with a direct answer, regulatory explanation, jurisdiction comparison, and practical guidance. |

### Example Usage

```
/compliance-review privacy-policy.pdf
/compliance-checklist onboarding a new remote employee in Ontario
/draft-notice PIPEDA breach — 1,200 customer email addresses exposed in phishing attack
/compliance-qa Do we need to report to FINTRAC when a client sends us $12,000 in cash?
```

---

## Skills

The plugin loads specialized regulatory knowledge automatically when you discuss relevant topics. You don't need to invoke skills manually — they activate when you ask about:

| Skill | Activates when you ask about |
|-------|----------------------------|
| Canadian Privacy Compliance | PIPEDA, Bill C-27, personal information, privacy policies, data breaches, consent |
| Canadian Employment & Labour | Employment standards, termination, notice periods, human rights, leave, minimum wage |
| Canadian Financial & Securities | FINTRAC, AML, KYC, LCTR, STR, OSC, CIRO, securities filings |
| Canadian Health & Safety | WHMIS, OH&S, workplace incidents, SDS, right to refuse, CCOHS |

---

## Important Disclaimer

This plugin provides general regulatory information for educational purposes. It is **not legal advice**. Canadian regulatory requirements are complex, change frequently, and depend heavily on your specific circumstances. Always consult a qualified lawyer or compliance professional before making compliance decisions, especially for high-stakes matters such as terminations, breach notifications, or regulatory filings.

---

## Setup

No environment variables or external service connections required. The plugin is fully self-contained.

---

## Author

Srivatsa Kasagar
Version 0.1.0
