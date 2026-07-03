---
name: avatar-builder
description: Use when a builder or founder wants to define their target customers / ideal-customer avatars (personas) for a product or idea. Asks a short, progress-counted interview, then produces THREE distinct, prioritized, research-grounded avatars — each with demographics, motivations (jobs-to-be-done), fears/desires, the acute problem, current alternatives, their language, a prioritized channel map, anti-fit, a one-line thesis, the riskiest assumption, and 3 strategic moves — ranked Primary/Secondary/Tertiary, delivered overview-first and (with your OK) saved as an overview plus one detailed file per persona.
version: "0.7.0"
allowed-tools: AskUserQuestion, WebSearch, Write, Read
---

# Avatar Builder

Turn a rough product idea into **three distinct, prioritized customer avatars**. Most products have
more than one plausible buyer; naming three and ranking them tells the user who to lead with.

Rules, enforced throughout:
- Each avatar is **narrow and genuinely distinct** — three different people (different jobs and contexts), not three flavors of one. Reject "everyone."
- Every field is a **hypothesis to validate**. Mark inferred fields `[assumption]`.
- **Same depth for all three.** No avatar gets more detail than the others.

## Step 1 — Interview (5 questions, show progress)
Open by telling the user exactly how many questions are coming, so they know the scope:
> "I'll ask you **5 quick questions** about your business, then build and rank your avatars."

Then ask them **one at a time**, and prefix each with progress so they always know how far along they
are — e.g. "**Question 2 of 5** — …". Wait for each answer; push back on vague ones.
1. What did you build (or want to build), in one sentence?
2. Who have you seen get the most value — who *lit up* using it?
3. What painful, expensive, or recurring problem does it kill for them?
4. What are they doing **today instead** (a tool, a hack, a person, or nothing)?
5. In their own words, how do they describe the problem? (real quotes if any)

If the user has little data, proceed but mark thin parts `[assumption]`.

## Step 2 — Build three avatars
Identify three distinct best-fit segments. For **each**, produce this full block — same depth for all three:
- **Name + tag** — a representative first name fitting the demographic + a one-liner (e.g. "Indie-hacker Ian, 34").
- **Persona snapshot** — age/life stage, role/title, location type, **household**, income & constraints, education, tech comfort.
- **A day in their life** — when/where the problem shows up, and the trigger moment.
- **Motivations (jobs to be done)** — functional / emotional / social job.
- **Drivers** — top fears/frustrations and desires/aspirations.
- **Goals & pain** — 1–2 measurable goals + the specific, quantified pain.
- **The acute problem** — the one that makes them act now.
- **Current alternative** — what they use instead, and why it fails them.
- **Their language** — 5–8 exact phrases they'd say.
- **Channel map** — watering holes they already frequent (subreddits, podcasts, creators, newsletters, search terms); the one channel to prioritize + why; hidden gems (small, high-engagement, low-competition); note to validate via SparkToro or lurking. Use WebSearch if it sharpens this.
- **Anti-fit** — who this is explicitly NOT for.
- **One-line thesis** — "[name] who struggles with [problem] because [current alternative] fails at [gap]."
- **Riskiest assumption + validation plan.**
- **So what — 3 moves:** message / channel / offer, each one line + one line on why it fits this persona.
- **Serve via** — how to serve them (e.g. membership / done-for-you / à-la-carte tool).

## Step 3 — Prioritize
Rank the three **Primary / Secondary / Tertiary**, scoring each on: acute pain, reachability, willingness
to pay, proof & word-of-mouth potential, and fit with the builder's strengths. Write one paragraph on
**why the Primary is the beachhead** and how the other two get served later.

## Step 4 — Deliver it (overview first; ask before saving files)
Never dump everything as one wall of text. Always present the **overview + ranking first**, then the
three detailed personas below, each under its own clear heading.

The overview should include: a **ranked comparison** (Primary/Secondary/Tertiary → serve-via), a
**one-line-plus short description of each persona**, the scoring of why that order, and the "who to
lead with" paragraph.

**Then ask before saving files.** If you're in a project (or the desktop app) where files can be
written, ask:
> "Want me to save these to your files — an overview `personas.md` plus one detailed file per persona?"

- If **yes**: write `personas.md` (the overview above, linking each persona file) plus one
  `<name-slug>.md` per persona (each holding that persona's full Step-2 block), then **open/surface the
  overview** so it renders in the preview panel.
- If **no**: leave it in the conversation.
- If files can't be written at all (e.g. a CLI with no project): just deliver the structured text —
  overview on top, three personas beneath. Don't ask.

## Step 5 — Optional: persona graphic
Offer to generate a **one-page SVG** poster summarizing all three personas (export to PNG for decks/social).
If yes: match their brand (ask for 1–2 colors + light/dark, or infer from their site; default clean with one
accent + a subtle growth motif in the header). Three columns ranked left→right (Primary highlighted); each a
dense dossier of the Step-2 fields; small monospace section labels; tall viewBox (≈1280×1000). Save as `.svg`.

## Step 6 — Close
Leave them with: **you can build for everyone or sell to someone — pick the someone to lead with, then go prove they exist.**
