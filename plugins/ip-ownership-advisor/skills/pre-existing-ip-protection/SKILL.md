---
name: pre-existing-ip-protection
description: This skill should be used when the user wants to document, disclose, or protect IP they developed before joining an employer, or when they ask about how to prove pre-employment development, build a defensible timeline, file a disclosure schedule, carve out prior IP from an employment agreement, or protect software they wrote before starting a job. Trigger phrases include "prove I made this before", "pre-existing IP", "prior inventions schedule", "GitHub commit history as evidence", "carve out my IP", or "protect my software from employer claim".
version: 1.0.0
---

# Pre-Existing IP Protection

A practical guide to documenting, disclosing, and carving out intellectual property you developed before employment — and building the evidentiary record needed to defend ownership if disputed.

> **Disclaimer:** Educational guidance only — not legal advice. Work with a licensed IP attorney to formalize any disclosure or carve-out.

## Why Documentation Matters

The core question in any employer IP dispute is: *when was this invention made?*

- If conception **and** reduction to practice both occurred before your start date, the employer's IAA claim is weak
- If either happened after your start date, or used company resources, the employer's position strengthens
- Documentation that existed **before** the dispute is orders of magnitude more credible than documentation created afterward

Build your record now, while it is contemporaneous.

## Evidence Hierarchy (Strongest to Weakest)

| Evidence Type | Why It's Strong | How to Preserve |
|---------------|----------------|-----------------|
| Signed, dated source code commits | Cryptographically timestamped by a third-party server | Export git log with `git log --pretty=format:"%H %ai %s"` and archive |
| Filed provisional patent application | USPTO stamp date is authoritative and public | Save receipt and application confirmation |
| Notarized lab notebook or design document | Third-party timestamp, tamper-evident | Notarize key design documents before employment |
| Cloud storage with version history | Timestamped by provider | Export version history from Google Drive / Dropbox |
| Email threads with technical content | Third-party server timestamps | Forward to personal account and archive |
| Slack / Discord messages with timestamps | Third-party server records | Export and archive |
| Witness testimony | Human memory, harder to verify | Collect written statements from collaborators |

## Step-by-Step: Building Your Pre-Employment Record

### 1. Export and Archive Your Git History

```bash
# Export full commit log with author dates and hashes
git log --pretty=format:"%H %ai %an %s" > commit-history.txt

# Create a signed tag at the current HEAD for future reference
git tag -s v-pre-employment-$(date +%Y%m%d) -m "Pre-employment snapshot"

# Archive the repository with preserved timestamps
git bundle create my-project-$(date +%Y%m%d).bundle --all
```

Store the bundle and commit log in at least two places: personal cloud storage with version history enabled, and a physical drive.

### 2. Generate a Dated Artifact Summary

Document every component you consider pre-existing IP:

```
IP Asset: [Name of algorithm / module / system]
File(s): [List of source files]
First commit: [SHA] on [date]
Description: [What it does, in plain language]
Development location: [Personal home office, personal equipment only]
Resources used: [None / personal laptop, personal GitHub account]
```

Have this document notarized or timestamped by a third-party service before your employment start date if possible.

### 3. Complete the Prior Inventions Schedule

When signing an IAA, most agreements include a prior-inventions schedule. Fill it out:

- List every piece of software, algorithm, or invention you want to retain
- Be specific: include project names, GitHub repository names, a brief description
- Do **not** leave it blank if you have pre-existing IP
- If the employer resists acknowledging the schedule, consult an attorney before signing

If you already signed with a blank schedule, document why (e.g., you misunderstood the form, the IP was not in a form you considered an "invention" at the time) and consult an attorney about a retroactive amendment.

### 4. Draft a Formal Disclosure Letter (Post-Employment)

If you are already employed and did not disclose pre-existing IP at onboarding, a formal written disclosure — sent to HR or Legal — creates a clear record. Have an attorney draft this. Key elements:

- Describe the pre-existing IP with specificity
- Assert your ownership under the applicable state statute (e.g., Cal. Lab. Code § 2870)
- Attach the evidence summary from Step 2
- Request a written acknowledgment that the company does not claim rights

This step carries risk: it surfaces the IP to your employer. Weigh that risk against the benefit of clarity before proceeding.

### 5. Maintain Clean Separation Going Forward

Prevent future disputes by keeping your independent work completely separate from your employment:

- Use personal devices exclusively for your LLC's work
- Use a personal email and personal GitHub account (not corporate SSO)
- Do not work on your personal IP during work hours or at the company's location
- Do not discuss your personal IP with colleagues using company communication tools
- Keep separate financial records for any revenue from your LLC

## LLC as a Holding Entity

Holding IP under a separate LLC (such as Enigma Strategic Ventures LLC) provides:
- Clear chain of title showing the IP was assigned to the LLC before employment
- A legal entity distinct from you personally, making it harder for an employer to argue you "invented" something in your individual capacity during employment
- A business structure that can receive licensing revenue or assignment proceeds

Ensure the LLC has a formal IP assignment agreement (you → LLC) dated **before** your employment start date for any pre-existing assets.

## What Not to Do

- Do not create backdated documents — this is fraud and will destroy your credibility
- Do not copy company code or data into your personal project
- Do not use company time or resources for your personal IP work
- Do not discuss your IP strategy with coworkers who might be required to report it
- Do not file patents under your personal name if the LLC is the intended owner (fix the assignment chain first)
