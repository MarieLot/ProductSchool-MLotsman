# Riverty Consumer Card: PM Certification Final Project

## What this repo is
My individual final project for the Product School PM certification (Riverty cohort 2), **BU Pay & Credit** case.
Challenge: *How might Riverty use its first consumer card to build a direct, everyday relationship with its users, growing usage and monetisation without undermining its merchant-first strategy?*
Scope: Germany, from a friends-and-family test launch (1,200 invitees, 4 months) to a launch recommendation.

## Hard rules
- **All data in `/data` is fictional practice data.** Never present any figure as a Riverty fact. Label numbers "pilot (practice data)" in every output.
- **No confidential Riverty information** goes into this repo or into prompts.
- **Cite the evidence.** Every claim names its source: interview IDs (N-01…N-12), ticket IDs (T-101…T-108), or the CSV and column.
- **Behaviour over opinion.** When what people say (interviews) conflicts with what they do (funnel, transactions), say so and favour the behavioural data. Name the conflict and what you'd check next. Don't average it away.
- **Show the arithmetic.** For any rate, give the numerator and denominator (e.g. 288 / 431 = 66.8% added to wallet).
- **Flag sample bias.** 639 of 1,200 invitees are employees. Treat approval, repayment and activation rates as likely optimistic.
- **Stay in phase.** In discovery and synthesis tasks (Modules 1–3), describe problems only. Don't propose features, a roadmap or solutions unless I ask. Solutions start at Module 4 (backlog scoring).
- **Respect the constraints.** The card platform is shared, so engineering, risk, finance and ops capacity is limited. Every proposition change needs regulatory approval, which takes months. Prefer scope that avoids re-approval.
- **Merchant-first test.** Every recommendation must say whether it sends spending to Riverty's partner merchants or away from them.

## PM point of view (always on)
For any research, data, market-sizing, lending, BNPL, card, e-commerce or product question, invoke the `anthropic-skills:pm-pov` skill first, before searching or answering. Do this even when the question looks simple or doesn't mention product management. If a question is clearly unrelated (for example a code change), skip the skill and say so in one line.

How it fits with the rules above:
- Use the skill's structure: What I found → Simple explanation → For Riverty / workshop relevance → Legal & compliance.
- **The Hard rules always win** over the skill. That means practice-data labels, evidence citations, arithmetic, phase limits and the merchant-first test apply inside every section.
- In Modules 1–3 the "For Riverty / workshop relevance" section describes problems only, with no solutions.
- Legal & compliance leads with Germany (BaFin: KWG, ZAG, BGB), since that is the project scope. Keep the Luxembourg (CSSF) and Netherlands (AFM and DNB: Wft, Wwft, BGfo) blocks short unless I ask for more.
- Public market and legal research from the web is allowed, but it is never mixed with `/data` figures, and external figures are labelled as external with their source.

## Who we design for
- **Lena, 32, Cologne.** Heavy BNPL user, mobile-first, no financial cushion. Uses pay later so money leaves only after she keeps the item. Has Klarna and PayPal, doesn't prefer Riverty.
- **Merchants (enterprise and SME).** They care about conversion, cost of acceptance, and whether the card sends customers to them.
- **Inside Riverty.** Engineering, risk, finance, operations and regulatory stakeholders.
- **Main competitor: the status quo.** A debit card in shops, whichever BNPL option checkout offers, and several apps to track it all.

## Repo structure
```
/data            raw case pack files (CSV + data-pack.md), read-only
/module-1        problem hook & value proposition
/module-2        AI synthesis (health & insights summary), persona, journey map, competitive advantages
/module-3        funnel / cohort / segment analysis
/module-4        backlog scoring (B1–B8), prioritisation
/module-5        success metrics, baselines, experiment design
/module-6        go-to-market, audience sizing
/final           final project deliverables
```
Each CSV in `/data` starts with one label line: skip the first row when loading.

## How to work with me
- **Confirm before creating any HTML page or document.** First propose its content as bullet points or a short description, then wait for my explicit OK. Only build it after I confirm, and apply any changes I ask for first.
- Before writing, briefly restate which module and deliverable we're on.
- When you summarise research, list contradictions and open questions at the end.
- If an output template exists in the module folder, fill it in. Don't invent a new format.
- Keep writing plain and short. These become slides.
