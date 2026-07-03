---
name: avatar-builder
description: Use when a builder or founder wants to define their target customers / ideal-customer avatars (personas) for a product or idea. Interviews the user, then produces THREE distinct, prioritized, research-grounded avatars — each a named persona with demographics, motivations (jobs-to-be-done), fears/desires, the acute problem, current alternatives, their language, a prioritized channel map, anti-fit, a one-line thesis, the riskiest assumption to validate, and 3 strategic moves — then ranks them so the user knows which to lead with.
version: "0.5.0"
allowed-tools: AskUserQuestion, WebSearch
---

# Avatar Builder

Turn a rough product idea into **three distinct, prioritized customer avatars**. Most products have
more than one plausible buyer; naming three and ranking them tells the user who to lead with.

Rules, enforced throughout:
- Each avatar is **narrow and genuinely distinct** — three different people (different jobs and
  contexts), not three flavors of one. Reject "everyone."
- Every field is a **hypothesis to validate**. Mark inferred fields `[assumption]`.
- **Same depth for all three.** No avatar gets more detail than the others.

## Step 1 — Interview
Ask these one at a time and wait for each answer. Push back on vague answers.
1. What did you build (or want to build), in one sentence?
2. Who have you seen get the most value — who *lit up* using it? Describe a specific real person if you can.
3. What painful, expensive, or recurring problem does it kill for them?
4. What are they doing **today instead** (current alternative — a tool, a hack, a person, or nothing)?
5. In their own words, how do they describe the problem? (ask for real quotes/messages)
6. What do you already know about them — rough age, role, where they spend time online?

If the user has little data, proceed but mark thin parts `[assumption]`.

## Step 2 — Produce THREE avatars
Identify three distinct best-fit segments. For **each** avatar, output this full block — same depth
for all three:

- **Name + tag** — a representative first name fitting the demographic + a one-liner (e.g. "Indie-hacker Ian, 34").
- **Persona snapshot** — age/life stage, role/title, location type, **household**, income & constraints, education, tech comfort.
- **A day in their life** — when/where the problem shows up, and the trigger moment.
- **Motivations (jobs to be done)** — functional / emotional / social job.
- **Drivers** — top fears/frustrations and desires/aspirations.
- **Goals & pain** — 1–2 measurable goals + the specific, quantified pain.
- **The acute problem** — the one that makes them act now.
- **Current alternative** — what they use instead, and why it fails them.
- **Their language** — 5–8 exact phrases they'd say.
- **Channel map** — watering holes they already frequent (subreddits, podcasts, creators, newsletters, search terms); the one channel to prioritize + why; hidden gems (small, high-engagement, low-competition); and a note to validate via SparkToro or lurking. Use WebSearch if it sharpens this.
- **Anti-fit** — who this is explicitly NOT for.
- **One-line thesis** — "[name] who struggles with [problem] because [current alternative] fails at [gap]."
- **Riskiest assumption + validation plan.**
- **So what — 3 moves:** message / channel / offer, each one line + one line on why it fits this persona.

## Step 3 — Prioritize the three
Rank them **Primary / Secondary / Tertiary.** Score each on: acute pain, reachability (where they
already gather), willingness to pay, proof & word-of-mouth potential, and fit with the builder's
strengths. Write one paragraph on **why the Primary is the beachhead** (lead here first) and how the
other two get served later. This ranking is the deliverable's point — never leave the three unranked.

## Step 4 — Optional: persona graphic
Offer to generate a **one-page SVG** summarizing all three personas — a shareable poster (export
to PNG for decks/social). If they say yes:
- **Match their brand.** Ask for 1–2 brand colors and a light/dark preference, or infer them from
  their site/product. Default to a clean theme with a single accent color; keep a subtle growth
  motif (a rising line/arrow labeled with a scale cue) in the header.
- **Layout:** three columns, ranked left→right (Primary highlighted with the accent color). Each
  column is a dense dossier with the same fields as Step 2 — name + tag, snapshot, jobs-to-be-done,
  acute problem, current alternative, their language, channels, anti-fit, riskiest assumption, the
  3 moves, and a "serve via" chip. Use small monospace section labels; keep every line short enough
  to fit the column width. Give the canvas a tall viewBox (≈1280×1000) so the columns fill it.
- Save it as an `.svg` file if the user is in a project.

## Step 5 — Close
Offer to save the avatars to files if the user is in a project. Then leave them with:
**you can build for everyone or sell to someone — pick the someone to lead with, then go prove they exist.**
