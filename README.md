# Serenity Skill

[![skills.sh](https://skills.sh/b/siisee11/serenity-skill)](https://skills.sh/siisee11/serenity-skill)

Serenity is an agent skill for researching high-growth public equities through supply-chain bottleneck analysis. It helps an AI agent map a major trend into physical constraints, identify overlooked public suppliers, falsify weak theses, and produce ranked watchlists or research memos.

This is research assistance, not personalized financial advice. Always verify current prices, filings, news, and company claims from primary sources.

## Install

Install with the `skills` CLI:

```bash
npx skills add siisee11/serenity-skill
```

Install specifically for Codex:

```bash
npx skills add siisee11/serenity-skill --skill serenity -a codex
```

Install globally for Codex:

```bash
npx skills add siisee11/serenity-skill --skill serenity -a codex -g
```

## Use

After installation, invoke it by name:

```text
Use $serenity to find overlooked US-listed companies exposed to AI data-center power bottlenecks.
```

Or:

```text
$serenity로 AI 광통신 공급망의 2차/3차 병목 수혜 후보를 찾아줘.
```

## What It Produces

- Bottleneck maps for secular growth trends.
- Public-company candidate screens.
- Ranked watchlists with evidence, risks, and next checks.
- Single-company research memos with thesis, catalysts, bear case, and falsification criteria.

## Source

The skill definition is in [`SKILL.md`](./SKILL.md), with the detailed framework in [`references/research-framework.md`](./references/research-framework.md).
