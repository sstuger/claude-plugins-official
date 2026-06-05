# IP Ownership Advisor

A Claude Code plugin for developers, engineers, and founders who need to navigate intellectual property ownership risks — especially when moving between employers or filing patents on independently developed work.

## Overview

When a developer joins a company they typically sign an **Invention Assignment Agreement** (IAA), which can transfer ownership of future inventions to the employer. If you developed software, algorithms, or other IP *before* joining the company but file patents *after* starting, you may face ownership disputes.

This plugin provides skills that activate automatically when you discuss these topics with Claude.

## Skills

### `invention-assignment-review`
Activates when you share or ask about an employment contract, IAA, or invention assignment clause. Guides you through the key risk factors: scope language, field-of-use definitions, prior-art carve-outs, and state-law constraints (e.g., California Labor Code § 2870).

### `pre-existing-ip-protection`
Activates when you need to document, disclose, or carve out IP you developed before employment. Helps you build a defensible record using GitHub commit history, dated design documents, and formal disclosure schedules.

### `patent-strategy`
Activates when you discuss provisional or non-provisional patent filings, conversion timelines, or claim drafting strategy. Covers the 12-month provisional window, cost estimates for conversion, and claim framing to emphasize pre-employment development.

## Commands

### `/ip-ownership-advisor:check`
Run a guided IP risk assessment. Paste your invention assignment clause (or describe your situation) and Claude will walk through the key risk factors, red flags, and recommended next steps.

## Important Disclaimer

This plugin provides **informational guidance only** — not legal advice. Always consult a licensed IP attorney before making decisions about patent filings, employment agreements, or IP disclosure. The analysis here is educational and does not create an attorney-client relationship.

## When to Use This Plugin

- You developed software or algorithms before joining a new employer
- You signed an invention assignment agreement and are uncertain what it covers
- You filed (or plan to file) a provisional patent under a personal LLC while employed
- You want to understand whether your employer can claim ownership of your pre-employment work
- You need to plan a non-provisional patent conversion strategy

## License

Apache 2.0
