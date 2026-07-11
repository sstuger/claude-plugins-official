# CLAUDE.md

## IP Document Handling Status — Omnibus Provisional (updated 2026-07-11)

**Holding policy:** The omnibus provisional application and its figure set are
HELD on the inventor's local machine only and are NOT committed to any
repository until the provisional filing is complete and confirmed by counsel.

Documents under hold, in `enigma-vault/local-hold/session-19-omnibus-redline/`
(gitignored via `local-hold/` in the enigma-vault `.gitignore`):

- `792026_00332Stuger_PROV_DRAFT_rev3.docx` — Jeff's original omnibus provisional draft
- `792026_00332Stuger_PROV_DRAFT_rev3_REDLINE_Stuger.docx` — inventor's tracked-changes redline (77 revisions, authored "Shaun Stuger")
- `792026_00332Stuger_FIGS_rev3.pdf` — 20-page figure set (FIG. 21–23 to be added per redline Note 5)

SHA-256 integrity hashes (computed Session 19, 2026-07-11; manifest copy lives
in the holding folder as `SHA256SUMS.txt`):

```
35a0a66945eec83a88a32f157444ae321b2701289cb881322bb76a5b3f7f885c  792026_00332Stuger_PROV_DRAFT_rev3.docx
d09d74e9fb26a2ef46a0b04c931ad523ee82fd9b8df1237633760effb9329b39  792026_00332Stuger_PROV_DRAFT_rev3_REDLINE_Stuger.docx
383a1b4c21b9c78e8c4e8b56717dcc53404fdc9185a126cf17bcb8ddb415ff1a  792026_00332Stuger_FIGS_rev3.pdf
```

**Once filing is complete and approved:** push these artifacts to the private
`sstuger/enigma-vault` repository (suggested location:
`filings/omnibus-provisional/`), alongside the assessment redline and session
context documents.

**Do NOT commit the application DOCX or figures PDF to this repository
(`claude-plugins-official`) under any circumstances.** This repo is public;
placing an unfiled patent application here could constitute public disclosure —
starting the 12-month §102(b) grace-period clock in the US and destroying
foreign filing rights (absolute-novelty jurisdictions).

## Files currently on this branch (`claude/ip-counsel-synopsis-xaAZG`)

- `IP-Session-2-IP-Counsel-Package-Synopsis.md` — IP strategy session context document
- `PROV_DRAFT_rev3_REDLINE.md` — markdown assessment redline (16 changes, 3 tiers)

These two markdown documents remain here temporarily until a dedicated,
firewalled local repository is established, at which point they move to
`enigma-vault` and should be removed from this public repo.

## Session ground rules

- Do not share any filing or IP material with anyone at Space Kinetic.
- Push only to branch `claude/ip-counsel-synopsis-xaAZG`; no edits to other
  branches or repositories without direction.
- All IP evidence and strategy documents are sensitive — default to the
  private `enigma-vault` repo for anything new.
