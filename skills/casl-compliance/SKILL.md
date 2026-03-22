---
name: casl-compliance
description: >
  This skill should be used when the user asks about "CASL", "Canada's Anti-Spam Legislation",
  "commercial electronic message", "CEM", "email marketing compliance", "SMS marketing",
  "express consent", "implied consent", "unsubscribe mechanism", "opt-in", "opt-out",
  "CRTC complaint", "spam", "electronic marketing Canada", or any question about
  whether a digital communication or marketing practice complies with Canadian anti-spam rules.
version: 0.1.0
---

# CASL — Canada's Anti-Spam Legislation

## Overview

CASL (S.C. 2010, c. 23) came into force July 1, 2014. It is one of the world's strictest anti-spam laws and applies to any **Commercial Electronic Message (CEM)** sent from or to a Canadian computer system. Violations can result in penalties up to **$1 million per violation for individuals** and **$10 million per violation for organizations**.

The regulator is the **CRTC (Canadian Radio-television and Telecommunications Commission)**.

---

## What is a Commercial Electronic Message (CEM)?

A CEM is any electronic message (email, SMS, instant message, or similar) where one of the **purposes** is to:
- Encourage participation in a commercial activity
- Promote a product, service, or person conducting commercial activity
- Promote a business opportunity

The test is **purpose**, not content. A single commercial purpose is enough — even if the message is mostly informational.

**Examples of CEMs:**
- Marketing emails, newsletters with promotional content
- Transactional emails that include upsell/cross-sell content
- SMS discount codes
- Instant messages promoting services
- "We miss you" re-engagement emails

**NOT CEMs (exemptions from consent requirement):**
- Pure transactional/relationship messages (order confirmations, password resets, account statements) with no promotional content
- Messages between individuals with a personal relationship
- Messages sent in response to a request, inquiry, or complaint
- Internal business communications (employee to employee, same organization)
- Messages to registered charities or political parties soliciting donations
- Due diligence messages in merger/acquisition transactions

---

## The Three Requirements for a Compliant CEM

Every CEM must satisfy all three:

### 1. Consent
The sender must have either **express** or **implied** consent from the recipient before sending.

**Express Consent**
- Recipient has explicitly opted in (checked a box, signed a form, verbally agreed)
- The opt-in request must clearly describe: the purpose of consent, who is seeking consent, and that the person can withdraw consent
- **Never** use pre-checked boxes — these do not constitute express consent
- Express consent does not expire unless withdrawn
- **Burden of proof is on the sender** — maintain records of when and how consent was obtained

**Implied Consent — Business/Non-Business Relationship**
| Type | Condition | Duration |
|------|-----------|---------|
| Existing business relationship | Purchase, lease, or barter within the past **2 years** | 2 years from last transaction |
| Existing non-business relationship | Donation, volunteer work, club membership within past 2 years | 2 years from last activity |
| Conspicuously published address | Recipient published their address (e.g., on a website) AND message is relevant to their role/function | No time limit, but only for role-relevant messages |
| Inquiry/application | Recipient made an inquiry or application within the past **6 months** | 6 months from inquiry |

**Important:** Implied consent is a temporary window to obtain express consent — use it to ask for opt-in, not as a permanent licence to market.

### 2. Identification
Every CEM must clearly identify:
- The **sender's name** (person or organization sending the message)
- If sending on behalf of another party, identify **both** the sender and the party on whose behalf the message is sent
- **Mailing address** (physical street address, not just a P.O. box)
- **One other contact** — phone number, email address, or web address

This information must be accurate and accessible **for at least 60 days** after the message is sent.

### 3. Unsubscribe Mechanism
Every CEM must include:
- A **functional unsubscribe mechanism** — link, reply address, or other electronic means
- The mechanism must be **easy to perform** — no fees, no login requirement, no excessive steps
- Unsubscribe requests must be **processed within 10 business days**
- Once someone unsubscribes, you **must not send further CEMs** to that address (even if they have a separate relationship with you)
- The unsubscribe mechanism must remain functional for **at least 60 days** after the message is sent

---

## CASL Compliance Checklist — Email/SMS Campaign

**Before sending:**
- [ ] Confirm consent type (express or implied) for every recipient
- [ ] Verify implied consent has not expired (2 years / 6 months as applicable)
- [ ] Consent records stored and retrievable for each recipient
- [ ] Sender name clearly identifies the organization
- [ ] Physical mailing address included
- [ ] Second contact (phone, email, or URL) included
- [ ] Unsubscribe link/mechanism present and functional
- [ ] Unsubscribe link leads to a simple, no-login mechanism
- [ ] Pre-checked consent boxes have been removed from all sign-up forms
- [ ] Suppression list is up to date (all prior unsubscribers excluded)

**After sending:**
- [ ] Process unsubscribe requests within 10 business days
- [ ] Log unsubscribe date and method
- [ ] Confirm sender identification remains accessible for 60 days

---

## Consent Request Best Practices

A compliant consent request must include:
1. The name of the organization seeking consent
2. The purpose(s) for which consent is sought (be specific — "to send you promotional offers about our products" not just "to contact you")
3. That the person can withdraw consent at any time
4. Contact information for the organization

**Good example:**
> ☐ I agree to receive promotional emails from Acme Corp (123 Main St, Toronto, ON) about our products and services. I understand I can unsubscribe at any time by clicking "unsubscribe" in any email.

**Bad example (non-compliant):**
> ☑ Yes, I agree to receive communications (pre-checked — invalid)
> ☐ I agree to receive updates (vague purpose — invalid)

---

## Penalties and Enforcement

| Violator | Maximum Penalty per Violation |
|---------|------------------------------|
| Individual | $1,000,000 |
| Organization | $10,000,000 |

The CRTC can also seek undertakings (binding commitments to change practices) and issue compliance orders.

**Private right of action:** CASL allows individuals to sue for damages (not yet in force — government has not proclaimed this section into force as of 2025, but monitor for activation).

Notable enforcement actions have included fines of $100K–$1.1M against organizations for sending CEMs without consent and failing to honour unsubscribes.

---

## Reference Files

- `references/casl-details.md` — Consent type decision tree, campaign review rubric, and CRTC complaint response guidance
