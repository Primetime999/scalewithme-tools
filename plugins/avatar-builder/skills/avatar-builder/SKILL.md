---
name: avatar-builder
description: Use when a builder or founder wants to define their best-fit customer or ideal-customer avatar for a product or idea. Interviews the user, then produces a structured avatar thesis — best-fit customer, acute problem, current alternative, their exact language, anti-fit, a one-line thesis, and the riskiest assumption to validate first.
version: "0.1.0"
allowed-tools: AskUserQuestion
---

# Avatar Builder

Help the user turn a rough product idea into a sharp best-fit-customer **thesis** they can sell
to. This is a thesis to *validate* later, not a final answer — favor sharp, specific guesses over
safe generalities. A best-fit avatar is narrow on purpose.

## Step 1 — Interview
Ask these one at a time and wait for each answer (plain questions, or AskUserQuestion where a few
options help). Do not move on until you have a real answer.

1. What did you build (or want to build), in one sentence?
2. Who have you seen get the most value — who *lit up* using it?
3. What painful, expensive, or recurring problem does it kill for them?
4. What are they doing **today instead** (the current alternative — a tool, a hack, a person, or nothing)?
5. In their own words, how do they describe the problem? (ask them to paste real quotes/messages if they have any)

Push back when answers are vague or trying to please everyone ("all small businesses",
"anyone who…"). Narrow them: which one person, in which situation, feels this most acutely?

## Step 2 — Produce the Avatar Thesis
Output exactly these fields:

- **Best-fit customer** — specific: role, context, stage. Not "small businesses."
- **The acute problem** — the one that makes them act *now*.
- **Current alternative** — what they use instead, and why it's failing them.
- **Their language** — 5–8 exact phrases they'd actually say (raw material for headlines/copy).
- **Anti-fit** — who this is explicitly *NOT* for. Say it plainly.
- **One-line thesis** — "[best-fit customer] who struggles with [problem] because [current alternative] fails at [gap]."
- **Riskiest assumption** — the one belief that, if wrong, breaks this avatar. This is what to validate first.

## Step 3 — Close
Offer to save the thesis to a file if the user is in a project. Then leave them with the
principle: **you can build for everyone or sell to someone — not both. Name the someone.**
