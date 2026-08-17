---
name: simplified-technical-english
description: Writes and rewrites procedures, instructions, manuals, warnings, and technical descriptions in Simplified Technical English (STE, ASD-STE100), applying controlled grammar, approved verb forms, noun-cluster limits, and sentence-length caps. Use when the user mentions Simplified Technical English, STE, or asks to simplify, control, or de-ambiguate a technical procedure, manual step, or safety warning for translation or non-native readers.
license: MIT
---

# Simplified Technical English (STE)

Controlled-language ruleset. The thresholds are the standard's specific numbers — apply them
exactly, don't round or approximate.

## Classify each passage first

- **Procedure** (steps, instructions, warnings): sentence limit **20 words**.
- **Description** (overview, theory of operation, background): sentence limit **25 words**.

A document can mix both — classify per sentence, not per document.

## Rules

- **Noun clusters: 3 words max.** Fix with prepositions (`of`, `for`, `on`) or a relative clause,
  not hyphenation. `fuel tank access panel removal procedure` → `procedure to remove the access
panel of the fuel tank`.
- **Verb forms: only these six** — infinitive, imperative, simple present, simple past, simple
  future, and past participle _used strictly as an adjective_ (`the closed valve`, never `has been
closed`). No continuous, perfect, or modal-stacked forms (`is opening`, `has been checked`,
  `should be able to`).
- **-ing words: technical noun/modifier only** (`operating temperature`, `connecting rod`). Never
  as a verb tense (`is checking`, `by checking...`).
- **Active voice always in procedures.** Passive allowed in descriptions only when the agent is
  unknown or irrelevant.
- **One instruction per sentence** — no chaining with "and"/comma.
- **Never drop subject, verb, or articles** to shorten a sentence.
- **Name the exact part/value/tool/location** — no "correctly," "properly," "as needed."
- **Paragraphs: one topic, 6 sentences max.** More steps → split into sub-procedures with headings.
- **Safety instructions: lead with the command or hazard condition**, not the consequence.
  Severity labels in order: `DANGER` → `WARNING` → `CAUTION` → `NOTE`.

## Self-check

1. Noun cluster >3 words?
2. Verb form outside the approved six?
3. Auxiliary-stacked tense?
4. `-ing` used as a verb?
5. Passive in a procedure, or passive-with-known-agent in a description?
6. Sentence >20 words (procedure) / >25 (description)?
7. More than one instruction per sentence?
8. Dropped subject/verb/article?
9. Vague instruction lacking a specific value/part/location?
10. Paragraph with >1 topic or >6 sentences?
11. Warning/caution not leading with command or hazard condition?

## Worked example

Original (45 words, one sentence):

> Prior to the installation of the replacement filter assembly, the old filter housing cover
> should be removed and it must be verified that the O-ring seal has not been damaged, since a
> damaged seal could potentially cause a leak which might result in equipment failure.

STE:

> Remove the cover of the filter housing before you install the replacement filter. Examine the
> O-ring seal. Make sure the seal is not damaged. A damaged seal can cause a leak. A leak can
> cause equipment failure.

## Workflow

1. Classify each passage (procedure/description).
2. Rewrite sentence by sentence against the rules.
3. Run the self-check list.
4. For long inputs, note next to the rewrite which rule changed each sentence.
