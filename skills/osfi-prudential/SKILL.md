---
name: osfi-prudential
description: >
  This skill should be used when the user asks about "OSFI", "Office of the Superintendent
  of Financial Institutions", "prudential compliance", "capital adequacy", "Basel III",
  "Basel IV", "CET1", "Tier 1 capital", "liquidity coverage ratio", "LCR", "NSFR",
  "stress testing", "ICAAP", "ORSA", "recovery plan", "resolution plan", "B-20",
  "mortgage stress test", "OSFI guideline", "federally regulated financial institution",
  "FRFI", "B-10", "B-13", "E-21", "technology risk", "outsourcing risk", "OSFI audit",
  "supervisory framework", or any question about OSFI's prudential regulatory requirements
  for banks, trust companies, insurance companies, or other federally regulated institutions.
version: 0.1.0
---

# OSFI Prudential Compliance

## Who OSFI Regulates

The Office of the Superintendent of Financial Institutions (OSFI) supervises and regulates all **Federally Regulated Financial Institutions (FRFIs)** in Canada:

| Institution Type | Examples |
|-----------------|---------|
| Chartered banks (Schedule I, II, III) | Big Six banks, foreign bank subsidiaries/branches |
| Trust and loan companies | Federal trust companies |
| Life insurance companies | Federal life and property & casualty insurers |
| Fraternal benefit societies | Insurance-based member organizations |
| Cooperative credit associations | Federal credit unions (rare) |
| Private pension plans | Federally regulated employer pension plans |

Provincial credit unions, provincial insurance companies, and provincially chartered trust companies are regulated by their provincial regulator, not OSFI.

---

## Capital Adequacy — Basel III/IV Framework

OSFI implements the Basel Committee on Banking Supervision (BCBS) framework through the **Capital Adequacy Requirements (CAR) Guideline**.

### Key Capital Ratios

| Ratio | OSFI Minimum | OSFI Target (Domestic Stability Buffer) |
|-------|-------------|----------------------------------------|
| Common Equity Tier 1 (CET1) | 4.5% of RWA | 8.0%+ (includes 2.5% conservation buffer + DSB) |
| Tier 1 Capital | 6.0% of RWA | 9.5%+ |
| Total Capital | 8.0% of RWA | 11.5%+ |
| Leverage Ratio | 3.0% of total exposures | 3.5%+ |

**Domestic Stability Buffer (DSB):** OSFI sets the DSB (currently 3.5% of RWA for D-SIBs) to absorb system-wide vulnerabilities. It can be lowered in a crisis to allow banks to use capital buffers.

**D-SIBs (Domestic Systemically Important Banks):** The Big Six (RBC, TD, BNS, BMO, CIBC, NBC) face a 1% D-SIB surcharge on top of standard minimums.

### Capital Quality Tiers

**CET1 (highest quality):** Common shares, retained earnings, accumulated other comprehensive income (AOCI), minus regulatory deductions (goodwill, intangibles, deferred tax assets)

**Additional Tier 1 (AT1):** Non-cumulative perpetual preferred shares, non-viability contingent capital (NVCC) instruments that convert to common equity at a trigger point

**Tier 2:** Subordinated debt with maturity >5 years; general allowances for credit losses; NVCC instruments

**NVCC requirement (Canadian-specific):** All non-common capital instruments issued by FRFIs must include a non-viability contingent capital clause — automatic conversion to common equity if OSFI or CDIC determines the institution is non-viable. This is a Canadian requirement beyond Basel minimums.

---

## Liquidity Requirements

### Liquidity Coverage Ratio (LCR)
- **Minimum:** 100%
- **Formula:** High-Quality Liquid Assets (HQLA) ÷ Net Cash Outflows over 30-day stress period ≥ 100%
- **Purpose:** Ensure FRFIs can survive a 30-day acute liquidity stress scenario
- **HQLA:** Level 1 (cash, central bank reserves, sovereign bonds) + Level 2A/2B (with haircuts)
- **Reporting:** Monthly to OSFI

### Net Stable Funding Ratio (NSFR)
- **Minimum:** 100%
- **Formula:** Available Stable Funding (ASF) ÷ Required Stable Funding (RSF) ≥ 100%
- **Purpose:** Ensure stable funding over a 1-year horizon
- **Reporting:** Quarterly to OSFI

### Liquidity Adequacy Requirements (LAR) Guideline
OSFI's LAR Guideline sets out LCR, NSFR, and additional Canadian liquidity metrics including the **Intraday Liquidity Monitoring** framework and **Net Cumulative Cash Flow (NCCF)** — a Canadian-specific metric requiring 30-day survival under stress.

---

## ICAAP — Internal Capital Adequacy Assessment Process

All FRFIs must conduct an annual ICAAP to assess whether their capital is adequate relative to their risk profile, beyond the minimum regulatory requirements.

### ICAAP Components
1. **Risk identification and assessment** — Identify all material risks: credit, market, operational, liquidity, strategic, reputational, legal/regulatory
2. **Capital quantification** — Estimate the capital needed to absorb each material risk under stress
3. **Stress testing** — Apply severe but plausible scenarios; assess capital adequacy under each
4. **Capital planning** — 3–5 year forward-looking capital projection
5. **Board and senior management oversight** — Board approves ICAAP; senior management implements
6. **OSFI review** — OSFI reviews ICAAP as part of the Supervisory Review and Evaluation Process (SREP)

---

## Key OSFI Guidelines

| Guideline | Topic | Key Requirements |
|-----------|-------|----------------|
| **B-20** | Residential Mortgage Underwriting | Mortgage stress test (qualifying rate = contract rate + 2% or 5.25%, whichever is higher); LTV limits; income verification |
| **B-10** | Outsourcing of Business Activities | Risk assessment for all material outsourcing; contracts must include audit rights, data security, business continuity; OSFI notification for material arrangements |
| **B-13** | Technology and Cyber Risk | Comprehensive cyber risk management framework; threat and vulnerability management; incident response and reporting to OSFI within 72 hours of material incident |
| **E-21** | Operational Risk Management | Sound operational risk practices: identification, assessment, monitoring, control, and reporting of operational risk |
| **E-23** | Model Risk Management | Governance over models used in risk measurement; validation requirements; model inventory |
| **B-7** | Derivatives Sound Practices | Risk management for derivatives: credit, market, liquidity, operational risks |
| **A-4** | Related Party Transactions | Arms-length requirements; board approval for material related-party transactions |
| **Corporate Governance** | Board and Management | Director independence, board composition, committee structure, fit and proper requirements for senior management |

---

## Mortgage Stress Test (OSFI B-20)

The B-20 mortgage stress test requires lenders to qualify borrowers at the higher of:
- The **contract mortgage rate + 2.00 percentage points**, or
- **5.25%** (the floor rate, reviewed periodically by OSFI)

**Applies to:** All federally regulated lenders (chartered banks, federal trust companies, federal credit unions)
**Does not apply to:** Provincial credit unions, private lenders, mortgage investment corporations (MICs)

Additional B-20 requirements:
- Maximum LTV of 80% for uninsured mortgages (properties >$1M cannot be insured)
- Income must be verified with reliable documentation
- Debt service ratios: GDS ≤ 39%, TDS ≤ 44%
- No co-lending structures designed to circumvent LTV limits

---

## Recovery and Resolution Planning

**Recovery Planning (OSFI)**
D-SIBs and other systemically important FRFIs must maintain a credible **Recovery Plan** — a playbook for restoring financial viability under severe stress without public support. Key elements:
- Governance: Board-approved; updated annually
- Stress scenarios: Idiosyncratic and market-wide
- Recovery options: Capital actions, asset sales, liquidity measures
- Indicators and triggers: Early warning metrics that trigger plan activation

**Resolution Planning (CDIC)**
The Canada Deposit Insurance Corporation (CDIC) leads resolution planning. D-SIBs must be resolvable over a weekend without taxpayer funds. Key requirement: **Total Loss Absorbing Capacity (TLAC)** — minimum 21.5% of RWA in loss-absorbing instruments that can be bailed in.

---

## OSFI Supervisory Framework

OSFI uses a risk-based supervisory approach:

**Composite Risk Rating (CRR):** OSFI assigns each FRFI a CRR of Low, Low-Medium, Medium, Medium-High, or High based on net risk and direction of risk. Higher ratings trigger more intensive supervision.

**Supervisory Cycle:** Based on CRR — D-SIBs supervised continuously; smaller institutions on 12–24 month cycles.

**Supervisory Actions:** Letters of concern → Memoranda of understanding → Orders to comply → Taking control of assets (most severe)

**Incident Reporting (B-13):** FRFIs must notify OSFI within **72 hours** of a material technology or cyber incident.

---

## Reference Files

- `references/osfi-details.md` — Capital ratio worked examples, ICAAP template outline, B-20 stress test calculator, and OSFI reporting calendar
