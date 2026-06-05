---
name: invention-assignment-review
description: This skill should be used when the user shares an employment contract, invention assignment agreement, IAA, IP assignment clause, or asks about whether their employer can claim ownership of software or inventions they created. Use when the user mentions phrases like "invention assignment", "IP assignment", "who owns my code", "employer IP claim", "work-made-for-hire", "prior inventions schedule", or describes a situation where they signed an agreement at onboarding and are unsure what IP they retained.
version: 1.0.0
---

# Invention Assignment Agreement Review

Helps you analyze the key risk factors in invention assignment agreements (IAAs) and identify whether your employer could claim ownership of IP you developed independently.

> **Disclaimer:** This skill provides educational guidance only — not legal advice. Consult a licensed IP attorney before acting on any analysis.

## Key Risk Factors to Evaluate

### 1. Scope of Assignment Language

Look for how broadly the agreement defines what is assigned:

- **Broad (high risk):** "all inventions conceived or reduced to practice during employment"
- **Narrower:** "inventions conceived using company resources or related to company business"
- **Red flag phrases:** "solely or jointly", "whether or not patentable", "in any field"

Ask: Does the scope extend to inventions developed entirely on personal time, with personal equipment, unrelated to the employer's business?

### 2. Field-of-Use and Relatedness Tests

Many agreements claim rights only if the invention relates to:
- The employer's current or reasonably anticipated business
- Work the employee performs for the employer
- Information the employer treats as confidential

Evaluate: Is the software or algorithm in the same technical domain as the employer's products? Even a hardware company could claim a software layer if it "relates to" their product roadmap.

### 3. Prior Inventions / Pre-Existing IP Schedule

Most well-drafted IAAs include a **Schedule A** (or equivalent) where the employee lists IP they developed before employment to carve it out. Key questions:

- Did the agreement include such a schedule?
- Did the employee fill it out completely and accurately?
- If the schedule was left blank or the employee declared "none," does that constitute a waiver of pre-existing IP?

**Critical issue:** Signing an IAA with a blank prior-inventions schedule — or checking "none" — does **not** automatically transfer pre-existing IP, but it creates evidentiary risk. Courts look at what the parties intended and what the employee actually owned at signing.

### 4. State Law Protections (Statutory Carve-Outs)

Several states restrict what employers can claim:

| State | Statute | Protection |
|-------|---------|------------|
| California | Labor Code § 2870 | Employees retain inventions developed entirely on own time, without company resources, unrelated to employer's business or R&D |
| Washington | RCW 49.44.140 | Similar carve-out for personal-time inventions |
| Illinois | 765 ILCS 1060/2 | Similar carve-out |
| Minnesota | Minn. Stat. § 181.78 | Similar carve-out |
| Delaware | Del. Code tit. 19 § 805 | Similar carve-out |
| North Carolina | N.C. Gen. Stat. § 66-57.1 | Similar carve-out |

Even if the IAA doesn't mention these statutes, they may apply by operation of law. For California specifically, Cal. Lab. Code § 2872 makes any IAA provision that purports to apply to § 2870-protected inventions void as against public policy.

### 5. Timing: When Was the Invention "Made"?

Courts typically look at:
- When the **conception** occurred (the mental act of creating the invention)
- When it was **reduced to practice** (built, tested, or described in enough detail to be operable)

If both conception and reduction to practice occurred before employment started, the employer's claim is much weaker — even if patents were filed after employment began.

**Key evidence:** Dated GitHub commits, design documents, lab notebooks, and communications all help establish a pre-employment timeline.

### 6. "Moonlighting" and Conflict of Interest Clauses

Separate from the IAA, many employment agreements include:
- Restrictions on outside business activities
- Non-disclosure obligations that could capture pre-existing technical knowledge
- Non-compete clauses (enforceability varies by state)

Check whether operating an LLC and filing patents under it violates any of these provisions — even if the IP itself is exempt.

## Analysis Framework

When reviewing an IAA clause, work through these questions in order:

1. **What does the scope language say?** → Does it cover personal-time work?
2. **Is there a prior-inventions schedule?** → Was it completed? What was declared?
3. **What is the employer's business?** → Does the invention relate to it?
4. **What state law applies?** → Are there statutory carve-outs?
5. **When was the invention made?** → Can you prove pre-employment development?
6. **Are there other clauses at play?** → Moonlighting, NDA, non-compete?

## Common Red Flags

- Agreement assigns inventions "conceived or reduced to practice" during employment with no carve-out for personal time
- Prior-inventions schedule was left blank or declared "none" when pre-existing IP existed
- Employer's business is broad enough to encompass the software domain
- No state-law carve-out applies because the work was done in a non-protective state
- The invention uses any company resources (even a laptop or corporate email)

## Recommended Next Steps

1. Locate and re-read the full IAA, including all schedules and exhibits
2. Identify when you conceived and reduced to practice each specific invention
3. Compile timestamped evidence (GitHub history, emails, design docs)
4. Determine which state's law governs the agreement
5. Consult an IP attorney to get a formal opinion letter on enforceability
