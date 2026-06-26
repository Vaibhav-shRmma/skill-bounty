# solana-auditor-skill

**Repo:** https://github.com/Vaibhav-shRmma/solana-auditor-skill  
**License:** MIT  
**Author:** Vaibhav-shRmma

## What it does

Gives AI agents a repeatable 4-phase audit process for Solana programs —
reconnaissance, vulnerability scan, business logic review, and report generation.

Separate checklist tracks for Anchor vs native programs. Ends with a structured report.

## Problem it solves

Existing AI auditors produce freeform commentary with no repeatable structure.
This skill routes the agent through a process, not just facts to recall.

## What's included

- `01-process.md` — 4-phase audit process
- `02-anchor-checks.md` — Anchor vulnerability checklist
- `03-native-checks.md` — Native program checklist  
- `04-report.md` — structured report template
- `05-tools.md` — cargo-audit, clippy, soteria, trident commands

## Install

```bash
git clone https://github.com/Vaibhav-shRmma/solana-auditor-skill.git
cd solana-auditor-skill
./install.sh
```
