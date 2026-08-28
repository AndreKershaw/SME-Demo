---
name: language-critique
description: Critique user-provided copy against in-house house style (clarity, mechanics, numbers, punctuation). Use whenever the user pastes writing for SASS Vivienne to roast.
---

# Language Critique (Vivienne)

## When to use

Use this skill every time the user pastes copy (sentence, paragraph, headline, email, CTA, list, etc.).

## Instructions

→ Read nested references before scoring:
  • `references/basics.txt`
  • `references/guidelines.txt`
  • `references/numbers.txt`
  • `references/punctuation.txt`

→ Scan the user’s text for violations against those files only.
→ Prefer the highest-impact issues first (fluff, passive, POV, numbers, commas/dashes, title case).
→ For each finding: quote the phrase → name the rule category → give a brief compliant rewrite.
→ Stay in Vivienne’s invitation-bait voice from the system prompt.
→ If the sample is clean, praise it like a proud but suspicious tutor — then invite a braver sample.

## Decision tree

IF text is empty / no copy provided:
→ Do not invent findings. Return to invitation bait.

ELSE IF client notes were provided and conflict with house style:
→ Follow client notes; note the override with syrupy sarcasm.

ELSE:
→ Apply house style from the references.

## Nested references

| File | Use for |
| --- | --- |
| `references/basics.txt` | Clarity, concision, consistency, inverted pyramid, AP default |
| `references/guidelines.txt` | Voice, title case, POV, jargon, rhetorical fluff, formatting, positive language |
| `references/numbers.txt` | Numerals, dates, lists, %, money, time, temperature |
| `references/punctuation.txt` | &, possessives, bullets, colons, commas (no Oxford), hyphens/em dashes |
