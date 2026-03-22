---
name: canadian-financial-securities
description: >
  This skill should be used when the user asks about "FINTRAC", "AML",
  "anti-money laundering", "KYC", "know your client", "suspicious transaction",
  "STR", "large cash transaction report", "LCTR", "OSC", "securities compliance",
  "IIROC", "CIRO", "beneficial ownership", "politically exposed person", "PEP",
  "terrorist financing", "ATF", "financial compliance", or any question about
  Canadian financial regulation and reporting obligations.
version: 0.1.0
---

# Canadian Financial & Securities Compliance

## Key Regulators

| Regulator | Mandate | Website |
|-----------|---------|---------|
| FINTRAC (Financial Transactions and Reports Analysis Centre of Canada) | AML/ATF reporting and intelligence | fintrac-canafe.gc.ca |
| OSC (Ontario Securities Commission) | Securities regulation in Ontario | osc.ca |
| AMF (Autorité des marchés financiers) | Securities & financial services in Quebec | lautorite.qc.ca |
| BCSC (BC Securities Commission) | Securities regulation in BC | bcsc.bc.ca |
| CIRO (Canadian Investment Regulatory Organization) | Self-regulatory for investment dealers and mutual fund dealers (successor to IIROC + MFDA) | ciro.ca |
| OSFI (Office of the Superintendent of Financial Institutions) | Federally regulated financial institutions | osfi-bsif.gc.ca |
| Bank of Canada | Monetary policy; bank notes | bankofcanada.ca |

## FINTRAC — AML/ATF Framework

### Who Must Comply (Reporting Entities)
Under the Proceeds of Crime (Money Laundering) and Terrorist Financing Act (PCMLTFA):
- Financial entities (banks, credit unions, caisses populaires)
- Life insurance companies and brokers/agents
- Securities dealers
- Money services businesses (MSBs) — including virtual currency exchange
- Real estate brokers/agents and developers
- Accountants and accounting firms
- Casinos
- Dealers in precious metals and stones
- British Columbia notaries

### Core Obligations

**1. Registration (MSBs)**
Money services businesses must register with FINTRAC before conducting business. Renewal every 2 years. Operating without registration = criminal offence.

**2. Know Your Client (KYC) — Client Identification**
Identify and verify every client before providing services:
- **Individuals:** government-issued ID (name, date of birth, address, document number, issuing jurisdiction)
- **Corporations:** certificate of incorporation + beneficial ownership information
- **Beneficial ownership:** Identify all individuals who own or control 25%+ of a corporation
- **Ongoing monitoring:** Regularly update KYC and flag changes

**3. Politically Exposed Persons (PEPs) and Heads of International Organizations (HIOs)**
- Domestic PEPs and HIOs: enhanced due diligence for higher-risk clients
- Foreign PEPs: **enhanced measures mandatory** — senior management approval required; source of funds/wealth must be established; ongoing monitoring required
- Family members and close associates of PEPs also subject to enhanced measures

**4. Reporting Requirements**

| Report Type | Trigger | Deadline |
|-------------|---------|---------|
| Large Cash Transaction Report (LCTR) | Receipt of $10,000+ in cash in a single transaction | Within 15 days |
| Large Virtual Currency Transaction Report (LVCTR) | Receipt of $10,000+ in virtual currency | Within 15 days |
| Suspicious Transaction Report (STR) | Reasonable grounds to suspect ML/TF | As soon as practicable (not later than 30 days after detection) |
| Terrorist Property Report (TPR) | Knowledge or reasonable grounds to believe property is owned/controlled by terrorist | Without delay |
| Casino Disbursement Report | Casino disburses $10,000+ to a person | Within 15 days |

**Structuring (tipping off prohibition):** Do not inform a client that an STR has been or will be filed. This "tipping off" is a criminal offence.

**5. Record-Keeping**
- Client identification records: 5 years after last transaction
- Transaction records: 5 years after transaction date
- Business relationship records: 5 years after end of relationship
- STR copies: 5 years after filing

**6. Compliance Program (mandatory)**
All reporting entities must implement a written compliance program with:
- Written AML/ATF policies and procedures
- Designated compliance officer (senior level)
- Risk assessment (clients, products, geographies, delivery channels)
- Ongoing employee training
- Effectiveness review (independent, every 2 years)

### STR Assessment Framework — Reasonable Grounds to Suspect

"Reasonable grounds to suspect" is a **lower standard** than "reasonable grounds to believe." Examples of red flags:
- Client reluctant to provide identification or provides inconsistent information
- Transaction has no apparent economic or lawful purpose
- Client conducts unusual series of transactions just below reporting thresholds (structuring)
- Client requests secrecy about nature of transaction
- Sudden large deposits inconsistent with known business profile
- Funds sent to/from high-risk jurisdictions
- Virtual currency transactions routed through multiple wallets to obscure trail

## Securities Compliance

### National Instruments (key)
- **NI 31-103** — Registration requirements, exemptions, and ongoing registrant obligations
- **NI 45-106** — Prospectus exemptions (accredited investor, offering memorandum, etc.)
- **NI 51-101** — Standards of disclosure for oil and gas activities
- **NI 52-109** — Certification of disclosure in issuers' annual and interim filings (CEO/CFO certification)
- **NI 52-110** — Audit committee requirements
- **NI 55-104** — Insider reporting requirements
- **NI 81-102** — Investment funds

### Registration Categories (NI 31-103)
- **Dealer:** Advises or transacts in securities as principal or agent
- **Adviser:** Manages portfolios or advises on securities for compensation
- **Investment Fund Manager (IFM):** Directs the business, operations, or affairs of an investment fund
- **Exempt Market Dealer (EMD):** Transacts in exempt market securities

### Continuous Disclosure (public companies)
- Annual information form (AIF) within 90 days of year-end
- Audited annual financial statements within 90 days
- Quarterly (unaudited) financial statements within 45 days
- MD&A accompanying all financial statements
- Material change reports: within 10 days of material change (press release immediately)
- Insider reports: within 5 days of transaction

### Prospectus Exemptions (common)
- **Accredited investor:** Net assets >$1M (excluding principal residence), or net income >$200K (or $300K with spouse) in each of the 2 preceding years
- **Offering memorandum (OM):** Available in most provinces; investor eligibility criteria and risk acknowledgement required
- **Friends, family and business associates:** Restricted to close relationships with a director, officer, founder, or control person
- **Minimum purchase:** $150,000+ per investor

## Reference Files

- `references/fintrac-aml.md` — Detailed FINTRAC red flags, STR drafting guidance, compliance program template
