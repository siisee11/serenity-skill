---
name: serenity
description: Research workflow for finding high-growth public stocks by mapping major technology or infrastructure trends into overlooked supply-chain bottlenecks. Use when Codex is asked to identify, screen, compare, or write research on potential multi-bagger stocks, AI infrastructure beneficiaries, second- or third-order suppliers, scarce components/materials/equipment, bottleneck arbitrage, watchlists, thesis memos, or due-diligence checklists. Produces evidence-based investment research, not personalized financial advice; current market data, filings, and news must be verified from sources.
---

# Serenity

## Overview

Use this skill to turn a broad growth trend into a falsifiable map of physical constraints, supplier candidates, and risk-ranked research outputs. The style is "AI-assisted supply-chain bottleneck research": identify where demand can exceed capacity, then find small or underfollowed public companies with direct leverage to that constraint.

## Operating Rules

- Treat outputs as research assistance, not personalized financial advice. Do not tell the user to buy, sell, or size a position unless they explicitly request a general framework.
- Verify current facts with browsing or primary sources because prices, filings, management, guidance, ownership, and market structure change quickly.
- Prefer primary sources: SEC filings, company investor relations, earnings call transcripts, exchange filings, technical docs, customer/supplier announcements, credible industry reports, and regulatory records.
- Default to US-listed public equities, a 6-24 month thesis horizon, and high-risk small/mid-cap candidates unless the user gives different constraints.
- Flag thin liquidity, dilution, promotional behavior, customer concentration, governance issues, geopolitical exposure, and unclear revenue timing early.
- Separate "interesting bottleneck" from "investable public equity." A real constraint is not enough if the listed company has weak exposure, poor balance sheet, or valuation already discounts the thesis.

## Workflow

1. Scope the search.
   - Clarify or assume geography, market cap range, liquidity floor, time horizon, excluded sectors, and risk tolerance.
   - State assumptions briefly before research.

2. Build the bottleneck map.
   - Start from the demand shock: AI compute, data centers, power grid, semiconductors, robotics, biotech tools, defense, etc.
   - Decompose into physical layers: raw materials, substrates, equipment, components, test/inspection, packaging, networking, power, cooling, logistics, software controls, and maintenance.
   - For each layer, ask: what has long lead times, few qualified suppliers, hard technical know-how, regulated capacity, customer qualification cycles, or fragile geography?

3. Find public suppliers.
   - Search each bottleneck layer for upstream and midstream suppliers, including small-cap firms, foreign ADRs, equipment vendors, specialty materials, and niche component makers.
   - Identify whether exposure is direct, indirect, or speculative. Prefer direct revenue or customer evidence.

4. Triage candidates.
   - Score each candidate on bottleneck purity, scarcity, customer validation, operating leverage, revenue timing, balance-sheet runway, valuation, liquidity, and bear-case severity.
   - Keep a candidate only if there is a clear answer to: "What must become scarce, who must buy from this company, and when could it show up in numbers?"

5. Cross-verify and falsify.
   - Look for substitutes, competing capacity, customer dual-sourcing, Chinese/Korean/Taiwanese/Japanese alternatives, delayed capex, cyclicality, insider selling, dilution, and management credibility issues.
   - Search for evidence that disproves the thesis before writing the bull case.

6. Produce the output.
   - For discovery tasks, return a ranked watchlist with short theses, evidence, key risks, and next diligence questions.
   - For deep dives, return a memo with thesis, supply-chain role, catalyst path, valuation sanity check, bear case, and what evidence would change the view.
   - Cite sources and label unverified inferences clearly.

## Reference Files

- Read `references/research-framework.md` for detailed scoring rubrics, search prompts, and output templates.
