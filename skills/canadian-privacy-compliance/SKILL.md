---
name: canadian-privacy-compliance
description: >
  This skill should be used when the user asks about "privacy compliance",
  "PIPEDA", "Bill C-27", "CPPA", "personal information", "data breach notification",
  "privacy policy review", "consent requirements", "cross-border data transfer",
  or any question about how Canadian privacy law applies to their organization.
  Covers federal PIPEDA, the proposed Consumer Privacy Protection Act (Bill C-27),
  and provincial privacy legislation across BC, Alberta, Ontario, and Quebec.
version: 0.1.0
---

# Canadian Privacy Compliance

## Governing Legislation

### Federal
- **PIPEDA** (Personal Information Protection and Electronic Documents Act) — applies to private-sector organizations collecting, using, or disclosing personal information in the course of commercial activities.
- **Bill C-27 / CPPA** (Consumer Privacy Protection Act) — proposed replacement for PIPEDA; substantially similar but adds stronger consent rules, data portability rights, and algorithmic transparency obligations. Not yet in force as of 2025; monitor for royal assent.

### Provincial (substantially similar)
- **PIPA BC** (BC Personal Information Protection Act) — applies to BC private-sector organizations in lieu of PIPEDA.
- **PIPA AB** (Alberta Personal Information Protection Act) — applies to Alberta private-sector organizations.
- **Law 25 / Quebec Act** (An Act to Modernize Legislative Provisions as regards the Protection of Personal Information) — applies to Quebec organizations; now fully in force with additional obligations (privacy impact assessments, automated decision-making disclosure, data minimization).
- **Ontario** — no substantially similar private-sector privacy law; PIPEDA applies. Public-sector is governed by MFIPPA and FIPPA.

## The 10 Fair Information Principles (PIPEDA)

Apply these principles when assessing any privacy practice or document:

1. **Accountability** — Designate a Privacy Officer; implement and enforce policies.
2. **Identifying Purposes** — Document why personal information is collected before or at collection.
3. **Consent** — Obtain meaningful consent; note exceptions (legal, emergency, publicly available).
4. **Limiting Collection** — Collect only what is necessary for the stated purpose.
5. **Limiting Use, Disclosure, and Retention** — Use only for collected purpose; retain only as long as needed.
6. **Accuracy** — Keep personal information accurate, complete, and up to date.
7. **Safeguards** — Use security appropriate to sensitivity (encryption, access controls, etc.).
8. **Openness** — Make privacy policies readily available.
9. **Individual Access** — Respond to access requests within 30 days.
10. **Challenging Compliance** — Establish complaint procedures.

## Breach Notification Requirements

### Federal (PIPEDA — Mandatory Breach Reporting, in force since 2018)
- **Trigger:** A breach of security safeguards involving personal information where it is **reasonable in the circumstances to believe** the breach creates a real risk of significant harm (RROSH).
- **Notify OPC:** As soon as feasible; use the OPC Breach Report form.
- **Notify affected individuals:** As soon as feasible when RROSH exists.
- **Maintain breach log:** All breaches (regardless of RROSH) must be logged and retained for 24 months; OPC may request log at any time.
- **Penalties for non-compliance:** Up to $100,000 per violation under PIPEDA; Bill C-27 proposes fines up to 3% of global revenue or $10M.

### Alberta (PIPA AB)
- **Trigger:** Real risk of significant harm.
- **Notify OIPC Alberta:** Without unreasonable delay.
- **Notify individuals:** Required when RROSH exists.

### Quebec (Law 25)
- **Trigger:** Any confidentiality incident (unauthorized access, use, communication, or loss) affecting personal information that presents a risk of serious injury.
- **Notify CAI (Commission d'accès à l'information):** Within 72 hours of becoming aware.
- **Notify individuals:** Required when risk of serious injury.
- **Incident register:** Maintain a confidentiality incident register.

## Consent Framework

**Express consent** (required for sensitive information): explicit opt-in, clear language.
**Implied consent** (appropriate for non-sensitive, obvious purposes): reasonable inference from context.
**Invalid consent situations:** conditions of service, bundled consents without granularity, post-collection requests (under Bill C-27 these are prohibited).

**Exceptions to consent (PIPEDA s.7):** law enforcement, emergencies threatening life, journalistic/artistic/literary purposes, business transactions (s.7.2), publicly available information (Regulations Specifying Publicly Available Information).

## Cross-Border Data Transfers

Under PIPEDA, personal information may be transferred to a third party (including outside Canada) for processing. The transferring organization remains **accountable** for protection during transfer. Use contractual safeguards (data processing agreements, standard contractual clauses equivalent). No PIPEDA prohibition on transfers to specific countries, but organizations must inform individuals transfers may occur and ensure comparable protection.

Quebec Law 25 **adds**: a privacy impact assessment (PIA) is required before transferring personal information outside Quebec. If the PIA reveals inadequate protection, the transfer cannot proceed unless justified and safeguards are in place.

## Privacy Impact Assessments (PIAs)

Conduct a PIA when:
- Launching a new product, service, or system involving personal information
- Transferring personal information outside Quebec (mandatory under Law 25)
- Implementing automated decision-making affecting individuals (mandatory under Bill C-27)
- Significantly modifying an existing system

PIA steps: identify personal information flows → assess risks → implement mitigations → document findings → review periodically.

## Key Regulators

| Regulator | Jurisdiction | Contact |
|-----------|-------------|---------|
| OPC (Office of the Privacy Commissioner of Canada) | Federal / PIPEDA | priv.gc.ca |
| OIPC BC (Office of the Information and Privacy Commissioner for BC) | BC / PIPA BC | oipc.bc.ca |
| OIPC Alberta | AB / PIPA AB | oipc.ab.ca |
| CAI Quebec | QC / Law 25 | cai.gouv.qc.ca |

## Reference Files

- `references/pipeda-details.md` — Detailed PIPEDA section-by-section analysis, Bill C-27 comparison, and model privacy policy template
