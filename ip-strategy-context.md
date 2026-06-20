# Context Document — IP Strategy Session
## For Continuity Across Sessions
**Prepared:** June 20, 2026

---

## The Inventor

**Shaun Stuger** — U.S. Air Force veteran, 20+ years in defense acquisition, intelligence community operations, and space technology. Held positions at AFLCMC, Parsons Corporation. Currently VP of Federal Growth at **Space Kinetic Corp.** B.S. Computer Science, MBA.

---

## The Four Inventions

| Invention | Description |
|---|---|
| **AI Strategic Intelligence Platform** | Parent concept / overarching architecture |
| **VERIS Intelligence** | Layered signal pipeline (L1 ingest → L3 escalation → L6 coalition). Applies Mean Field Game theory and Stackelberg game dynamics to space domain awareness |
| **DYAD-Prime** | Staged adversarial reasoning engine: Stage 1 classical game theory → Stage 2 Perfect Bayesian Equilibrium → Stage 3 deception modeling |
| **StackGlue** | 7-layer agentic AI orchestration stack solving cross-agent lifecycle management and interlayer orchestration |

**Claims status:**
- VERIS + DYAD-Prime: **49+ claims across 9 clusters — provisionals filed**
- StackGlue: **8 patent claims drafted** — provisionals filed
- All filings recent as of June 2026

---

## Critical Timeline

| Date | Event |
|---|---|
| July 6–13, 2025 | GitHub public repo — learning phase (satellite imagery, graph RAG, LLM frameworks). **43 days pre-employment** |
| **July 29, 2025** | Microsoft Copilot session — platform named, architecture defined, target market identified, roadmap created. GitHub repo created same day. **20 days pre-employment.** Explicit statement of personal purpose in session. |
| July 31, 2025 | Local git commit 03:23 — never pushed. Cryptographically hashed, cannot be backdated |
| **August 5, 2025** | Signed INDA with Space Kinetic Corp. **Exhibit A (Prior Inventions list) left blank.** No legal counsel before signing. Repo was 6 days old; Copilot session was 7 days prior |
| September 7, 2025 | StackGlue — 8 patent claims drafted in Copilot, documented as personal/unrelated to Space Kinetic |
| May 2026 | Inventor narrative and IP counsel package committed to `sstuger/enigma-vault` |
| **June 2026** | Provisionals filed. Attorney consultations begun |

---

## The Central Legal Problem

INDA signed August 5, 2025 with **blank Exhibit A** (Prior Inventions schedule). Core conception and GitHub repository both predated signing by 6–7 days. Inventor did not have legal counsel at signing and did not understand the legal significance of leaving Exhibit A blank.

**Risk:** Space Kinetic could assert ownership under the INDA assignment clause despite pre-employment conception.

---

## The Four Legal Questions

1. Can Exhibit A be amended or supplemented retroactively?
2. Does **California Labor Code §2870** carve-out apply? (Inventions developed on personal time, without employer resources, unrelated to employer's business — Space Kinetic is a hardware/space company, not an AI software company)
3. Provisional patent filing sequencing across the four inventions
4. Timing and structure of CEO/CTO conversation at Space Kinetic — before or after filing, and on what terms

---

## Evidence Package

Located in `sstuger/enigma-vault/evidence/prior-art/`

| Artifact | What It Proves |
|---|---|
| Microsoft Copilot CSV export | 466-message conception session. Server timestamps (not inventor-controlled). Explicit personal-purpose statement. July 29, 2025 |
| Git bundle (all branches) | Cryptographically hashed. Includes July 31 local commit predating any push. Cannot be backdated |
| GitHub public repo activity | Learning phase July 6–13, 2025 — 43 days pre-employment |
| StackGlue Copilot CSV | 8 claims drafted September 7, 2025, documented as personal |

---

## Attorney Consultations — Status

**First attorney (consult):**
- Led with "I'm not sure I can help you" before hearing any facts
- Disclosed he doesn't specialize in CA Labor Law
- Felt the signed contract carries significant weight; raised concerns about timeliness of disclosure
- Assessed that pre-employment R&D "didn't matter as much because of the legal implications of the contract"
- Provided scattered advice without a clear through-line
- **Assessment: Pass. Premature conclusion, incomplete §2870 analysis, poor fit**

**Second attorney (consult):**
- Reviewed employment contract (INDA)
- Preliminary read: contract carries enough weight because it was signed and disclosure was not timely
- Has not yet fully digested the evidence package
- **Assessment: Preliminary only — §2870 analysis not yet completed**

**Key pushback on attorney reads so far:**
- §2870 analysis not yet completed — cannot be waived by contract
- Space Kinetic is a hardware company — relatedness prong of §2870 likely favors inventor
- Assignment clause may only reach inventions *conceived during employment* — July 29 date may fall outside scope entirely
- Third-party timestamps (Microsoft, GitHub) are not self-serving documentation

**What the right attorney looks like:**
- Specializes in inventor's rights disputes, not just employment agreements
- Leads with questions about timeline and documentation
- Runs §2870 analysis before assessing contract weight
- Asks: does the assignment clause reach pre-employment conception?

**One consensus point from both consultations:** File provisionals as soon as possible. ✓ Done.

---

## Strategic Positioning Work Completed

A full government market positioning framework was developed covering:

- **Core capability gap narrative:** Existing tools treat adversaries as random (Monte Carlo) or static (Palantir, DCGS). VERIS/DYAD model adversaries as rational, belief-updating agents — a gap no fielded government tool currently fills
- **Complementary positioning vs. Monte Carlo:** VERIS feeds live-updated inputs; DYAD replaces random adversary assumption with PBE computation. Message: *not a replacement, a missing layer*
- **Tool matrix:** VERIS/DYAD/StackGlue mapped against Monte Carlo, Palantir Gotham/Foundry, DCGS, JCATS/STORM, AFSIM, Recorded Future, IBM i2, MITRE ATT&CK, IDA/RAND models, NGA/GEOINT platforms
- **5 unique differentiators** for SBIR proposals and white papers
- **SBIR target alignment:** AFRL, DARPA (Gamebreaker, COMPASS), ONR, NGA/ODNI, Space Force, OSD/CAPE
- **Two-sentence elevator pitch** drafted

### Elevator Pitch
> "The government's existing tools are excellent at modeling what adversaries have done and what *might* happen probabilistically. VERIS and DYAD-Prime are the missing layer — they model what a rational adversary *will* do next, computed in real time from live strategic signals, using game-theoretic frameworks that have been in the academic literature for decades but never operationalized at decision-relevant speed."

---

## Open Items / Next Steps

- [ ] Find attorney who specializes in inventor's rights / pre-employment IP disputes, CA §2870 experienced
- [ ] Get full §2870 analysis applied to Space Kinetic's actual business scope
- [ ] Confirm INDA assignment clause language — does it reach pre-employment conception?
- [ ] Determine timing of Space Kinetic CEO/CTO conversation (before or after further legal counsel)
- [ ] Upload provisional filing artifacts to `sstuger/enigma-vault/evidence/prior-art/`
- [ ] Develop technical disclosure documents for each invention (feed into non-provisional applications)
- [ ] Develop scenario-based complementary positioning examples (concrete Monte Carlo failure mode story)
- [ ] Draft two-pager on complementary positioning for government customers (readable without inventor in the room)
- [ ] Identify first SBIR topic to target and begin proposal development

---

## Repository Reference

- **Primary repo:** `sstuger/enigma-vault` (private)
- **Evidence path:** `enigma-vault/evidence/prior-art/`
- **Working branch (claude-plugins-official):** `claude/ip-counsel-synopsis-xaAZG`

---

*Use this document to open the next session. All legal assessments are analytical observations, not legal advice. Retain qualified IP counsel before acting on any legal strategy.*
