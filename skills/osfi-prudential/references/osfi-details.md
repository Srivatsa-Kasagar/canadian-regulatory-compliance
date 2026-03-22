# OSFI Prudential Deep Reference

## Capital Ratio Worked Example

**Scenario:** A mid-size Schedule I bank with $50B in Risk-Weighted Assets (RWA)

| Capital Component | Amount | Calculation |
|------------------|--------|-------------|
| Common shares issued | $3.0B | — |
| Retained earnings | $4.5B | — |
| AOCI (net of tax) | $0.2B | — |
| Less: Goodwill | ($0.8B) | Regulatory deduction |
| Less: Other intangibles | ($0.3B) | Regulatory deduction |
| **CET1 Capital** | **$6.6B** | |
| **CET1 Ratio** | **13.2%** | $6.6B ÷ $50B |
| AT1 instruments (NVCC preferred) | $1.0B | — |
| **Tier 1 Capital** | **$7.6B** | CET1 + AT1 |
| **Tier 1 Ratio** | **15.2%** | $7.6B ÷ $50B |
| Tier 2 (subordinated debt) | $1.5B | — |
| **Total Capital** | **$9.1B** | |
| **Total Capital Ratio** | **18.2%** | $9.1B ÷ $50B |

**Interpretation:** All ratios exceed OSFI minimums. CET1 at 13.2% exceeds the 8.0% target (4.5% minimum + 2.5% conservation buffer + 1.0% D-SIB surcharge), providing a 5.2% buffer.

---

## ICAAP Template Outline

Use this structure when preparing or reviewing an ICAAP submission:

### Section 1: Executive Summary
- ICAAP purpose and scope
- Summary of material risks identified
- Assessment of capital adequacy (current and forward-looking)
- Key conclusions and management actions

### Section 2: Business Overview and Strategy
- Business model description
- Strategic plan (3–5 years)
- Key business risks arising from strategy

### Section 3: Risk Identification and Assessment
For each material risk, document:
- Risk definition and how it arises in the business
- Current risk level (low/medium/high)
- Risk controls and mitigants in place
- Residual risk level after mitigants

**Minimum risk categories to address:**
- Credit risk (including concentration risk)
- Market risk (interest rate, FX, equity)
- Operational risk (including cyber, conduct)
- Liquidity risk
- Interest rate risk in the banking book (IRRBB)
- Strategic/business risk
- Reputational risk
- Regulatory/legal risk

### Section 4: Capital Quantification
- Pillar 1 capital requirements (regulatory minimum)
- Pillar 2 add-ons for risks not fully captured in Pillar 1
- Internal capital target (above regulatory minimum)
- Methodology for quantifying each risk type

### Section 5: Stress Testing
- Scenario descriptions (at least 3: baseline, moderate stress, severe stress)
- Impact on capital ratios under each scenario
- Management actions available under each scenario
- Recovery threshold identification

### Section 6: Capital Planning
- 3–5 year capital projection under base and stress scenarios
- Planned capital issuances or redemptions
- Dividend policy and retained earnings assumptions
- Triggers for capital actions

### Section 7: Governance and Controls
- Board and senior management oversight of ICAAP
- Internal audit review findings
- ICAAP update frequency and owner

---

## B-20 Mortgage Stress Test — Qualifying Rate Calculator

**Step 1:** Identify the contract rate offered to the borrower (e.g., 5.79% 5-year fixed)

**Step 2:** Calculate the qualifying rate:
- Contract rate + 2.00% = 5.79% + 2.00% = **7.79%**
- OSFI floor rate = **5.25%**
- **Qualifying rate = higher of the two = 7.79%**

**Step 3:** Apply qualifying rate to maximum debt service ratios:
- **GDS ≤ 39%:** (Annual mortgage payments + property taxes + heat + 50% condo fees) ÷ Gross Annual Income
- **TDS ≤ 44%:** (GDS items + all other debt payments) ÷ Gross Annual Income

**Example:**
- Gross annual income: $180,000
- Property: $900,000 purchase, 20% down ($180,000), $720,000 mortgage
- Monthly payment at 7.79% over 25 years: ~$5,320/month
- Annual mortgage: $63,840; property tax: $7,200; heat: $2,400
- GDS: ($63,840 + $7,200 + $2,400) ÷ $180,000 = 40.8% → **EXCEEDS 39% limit → does not qualify**

---

## OSFI Regulatory Reporting Calendar

| Report | Frequency | Due Date |
|--------|-----------|---------|
| Capital Adequacy Return (CAR) | Quarterly | 30 days after quarter-end |
| Liquidity Coverage Ratio (LCR) | Monthly | 15 days after month-end |
| Net Stable Funding Ratio (NSFR) | Quarterly | 30 days after quarter-end |
| Net Cumulative Cash Flow (NCCF) | Monthly | 15 days after month-end |
| Large Exposure Return | Monthly | 30 days after month-end |
| Mortgage data (B-20 related) | Quarterly | 30 days after quarter-end |
| Annual ICAAP submission | Annual | Within 90 days of fiscal year-end |
| Recovery Plan update | Annual | As directed by OSFI |
| Material outsourcing notification | As needed | Before arrangement commences |
| Cyber/technology incident | As needed | Within 72 hours of discovery |

---

## Common OSFI Examination Findings

**Capital:**
- RWA calculations using incorrect risk weights for asset classes
- Failure to deduct all required items from CET1 (e.g., pension deficits, deferred tax)
- NVCC provisions missing or deficient in AT1/T2 instruments

**Liquidity:**
- Mis-categorization of assets as HQLA (encumbered assets included)
- Intraday liquidity monitoring gaps
- Funding concentration in wholesale funding not adequately stress-tested

**B-20 Mortgage:**
- Income not independently verified (relying solely on borrower-declared income)
- GDS/TDS calculations using understated property taxes or heat costs
- Co-lending arrangements that effectively circumvent LTV caps

**Operational/Technology (B-13):**
- No formal technology risk appetite statement
- Cyber incidents not escalated to board within required timeframe
- Third-party technology providers not subject to OSFI-compliant contractual controls
- Insufficient patch management and vulnerability scanning

**Outsourcing (B-10):**
- Material outsourcing arrangements not notified to OSFI in advance
- Contracts missing audit rights, sub-contracting restrictions, or exit provisions
- Business continuity testing not conducted for critical outsourced services
