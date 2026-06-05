---
name: patent-strategy
description: This skill should be used when the user asks about patent strategy for independently developed software or algorithms, specifically around provisional patents, converting a provisional to a non-provisional, patent claims drafting, the 12-month provisional window, patent costs, or filing under an LLC. Trigger phrases include "convert provisional patent", "non-provisional application", "patent claims for my algorithm", "12-month window", "patent filing costs", "patent under LLC", "patent strategy for pre-employment IP", or "provisional to non-provisional".
version: 1.0.0
---

# Patent Strategy for Independently Developed Software

Covers the provisional-to-non-provisional conversion process, claim drafting strategy for independently developed algorithms, timing considerations, and cost planning.

> **Disclaimer:** Educational guidance only — not legal advice. Patent prosecution requires a licensed patent attorney or agent. Incorrect filings can permanently forfeit patent rights.

## The Provisional → Non-Provisional Pipeline

### What a Provisional Patent Application Gives You

A provisional patent application (PPA) filed with the USPTO:
- Establishes a **priority date** — the date that counts for prior art purposes
- Is **never examined** and never becomes a patent on its own
- Gives you **12 months** to file a non-provisional application claiming that priority date
- Allows you to use "Patent Pending" on your product

If you do not file a non-provisional within 12 months, the provisional expires and the priority date is **permanently lost**.

### The 12-Month Clock

```
PPA filing date  ──────────────────────────────────► Deadline (12 months later)
      │                                                        │
      │   You can file non-provisional at any point            │
      │   during this window                                   │
      │                                                        │
      └── "Patent Pending" status active throughout ──────────┘
```

**Miss the deadline → lose the priority date.** You may still be able to file a non-provisional, but it will be judged against any prior art published after your original priority date — including your own public disclosures.

### What the Non-Provisional Application Includes

A complete non-provisional utility patent application contains:
1. **Specification** — detailed written description of the invention
2. **Claims** — the legally enforceable boundaries of the patent right
3. **Abstract** — brief summary
4. **Drawings** — where applicable (often essential for software/algorithm patents)
5. **Oath/Declaration** by the inventor
6. **Assignment document** — if ownership is being transferred to an LLC

## Claim Drafting Strategy for Pre-Employment IP

### Emphasize What Predates Employment

When the patent's legitimacy depends on establishing pre-employment invention:
- Drafting should **highlight the novel features that were conceived before employment**
- Avoid claims that read on functionality added or refined after joining the company
- Use the GitHub commit history and design documents to map claim elements to pre-employment work

### Independent vs. Dependent Claims

Structure claims in layers:
- **Independent claims** — broadest, stand alone, cover the core innovation
- **Dependent claims** — narrow the independent claims to specific embodiments

For pre-employment IP, ensure at least one broad independent claim is fully supported by pre-employment documentation alone. If you added improvements after employment, consider whether those improvements are worth claiming separately (they may be employer-owned).

### Algorithm and AI/ML Patent Considerations

Software and AI/ML patents face eligibility challenges under 35 U.S.C. § 101 (Alice/Mayo framework). To improve allowance odds:
- Frame claims around a **specific technical improvement** to a computer system, not just an abstract mathematical concept
- Tie the algorithm to a concrete technical result (e.g., improved accuracy in a specific domain, reduced computational complexity)
- Include hardware-specific language where appropriate ("a processor configured to...")
- Describe the unconventional combination of steps, not just the result

### Framing Independent Development in the Specification

The specification should explicitly establish:
- The development environment (personal devices, personal accounts, no company involvement)
- The timeline of conception and reduction to practice
- That the technology is distinct from and not dependent on the employer's systems

Your attorney can help frame this without making the specification read as a legal argument.

## Cost Planning

### Typical Fee Ranges (US, 2025 estimates)

| Service | Cost Range | Notes |
|---------|-----------|-------|
| Provisional drafted from scratch by attorney | $3,000–$6,000 | Depends on complexity |
| Provisional drafted by inventor, filed pro se | $320 USPTO fee (small entity) | Risky without counsel |
| Non-provisional drafted from scratch by attorney | $8,000–$15,000+ | Complex AI/ML can be higher |
| Non-provisional converting a quality provisional | $3,000–$6,000 | Savings depend on provisional quality |
| Non-provisional converting a weak provisional | $6,000–$10,000 | Attorney must essentially redraft |
| USPTO filing fee (small entity, 3 independent / 20 total claims) | ~$800–$1,600 | Scale with number of claims |
| USPTO filing fee (micro entity) | ~$400–$800 | Income and prior filing limits apply |

**Fixed-fee structures** are common for non-provisional conversions:
- ~$2,500 if the attorney drafted the provisional (they know the tech)
- ~$5,500 if drafting from scratch (no prior provisional or low-quality provisional)
- Middle ground ($3,500–$4,500) for converting a detailed, well-structured provisional

### Retainer vs. Fixed Fee

Many IP boutiques use:
- **Retainer** (e.g., $3,000) applied against hourly billing or fixed fees
- **Fixed fee** for defined deliverables (drafting, filing, responding to Office Actions)
- Hourly for open-ended tasks (prosecution strategy, litigation support)

Clarify whether the fixed fee includes USPTO filing fees, or only attorney fees.

## Entity Status Matters

Filing under a small entity (fewer than 500 employees, not large-entity assignee) reduces USPTO fees by ~60%. Filing under micro entity reduces them by ~80% if you qualify (income limits apply, and you cannot have been named on more than four prior patent applications).

If the patent is assigned to an LLC, the LLC's entity status applies, not yours individually.

## Filing Under an LLC

To assign a patent to your LLC:
1. File with yourself as inventor (inventors are individuals, not entities)
2. Execute an **Assignment Agreement** transferring rights from inventor to the LLC
3. Record the assignment with the USPTO (USPTO Assignment Division)

If the LLC was formed and the assignment was executed **before** your employment started, this strengthens the chain of title. If the assignment was executed after employment started, document clearly that it covers a pre-employment invention.

## Timeline Checklist

- [ ] Confirm exact PPA filing date and calculate the 12-month deadline
- [ ] Audit claims you want in the non-provisional against your pre-employment evidence
- [ ] Choose an attorney with software/AI patent prosecution experience
- [ ] Verify entity status (small / micro entity) for fee reduction
- [ ] Execute and record assignment from inventor to LLC before filing non-provisional
- [ ] File non-provisional with at least 30 days to spare before the deadline
