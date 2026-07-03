---
name: avatar-builder
description: Use when a builder or founder wants to define their target customer / ideal-customer avatar (persona) for a product or idea. Interviews the user, then produces a personified, research-grounded avatar — a named persona with demographics, motivations (jobs-to-be-done), fears and desires, the acute problem, current alternatives, their exact language, the channels where they already pay attention (with one to prioritize), anti-fit, a one-line thesis, and the riskiest assumption to validate first.
version: "0.3.0"
allowed-tools: AskUserQuestion, WebSearch
---

# Avatar Builder

Turn a rough product idea into a **personified, research-grounded customer avatar** the user can
build messaging, channels, and offers around. Enforce two rules throughout:
- A best-fit avatar is **narrow on purpose** — reject "everyone" and "small businesses."
- Every field is a **hypothesis to validate**, not a fact. The fastest way to be wrong is to
  invent a persona from assumptions. Mark inferred fields `[assumption]`.

## Step 1 — Interview
Ask these one at a time and wait for each answer. Push back when answers are vague — which *one*
person, in which situation, feels this most acutely?
1. What did you build (or want to build), in one sentence?
2. Who have you seen get the most value — who *lit up* using it? Describe a specific real person if you can.
3. What painful, expensive, or recurring problem does it kill for them?
4. What are they doing **today instead** (current alternative — a tool, a hack, a person, or nothing)?
5. In their own words, how do they describe the problem? (ask for real quotes/messages)
6. What do you already know about them — rough age, role, where they spend time online?

If the user has little data, proceed but mark the thin parts `[assumption]`.

## Step 2 — Produce the Avatar
Personify it — a representative human, not a category.

**Persona snapshot**
- **Name + tag** — a representative first name that fits the demographic, plus a one-liner (e.g. "Indie-hacker Ian, 34").
- **Age / life stage**, **role or title**, **location type** (e.g. remote, mid-size US city).
- **Household** — living situation, family, anything shaping their time, money, and risk tolerance.
- **Income & constraints**, **education**, **tech comfort**.

**A day in their life** — 2–3 sentences: when and where the problem shows up, and the trigger moment.

**Motivations — jobs to be done**
- **Functional job** — the practical outcome they want.
- **Emotional job** — how they want to *feel* (e.g. competent, in control, legitimate).
- **Social job** — how they want to be *seen* by peers, customers, or a boss.

**Drivers** — their top **fears/frustrations** and top **desires/aspirations**.

**Goals & pain** — 1–2 measurable goals and the specific, quantified pain.

**The acute problem** — the one that makes them act *now*.

**Current alternative** — what they use instead, and why it fails them.

**Their language** — 5–8 exact phrases they'd say (voice-of-customer, for hooks and copy).

**Where they pay attention (channel map)** — how you actually reach them:
- **Watering holes** they already frequent: specific subreddits, podcasts, YouTubers/creators, newsletters, communities, and the **search terms/questions** they Google.
- The **ONE channel to prioritize first**, with a reason (highest concentration of their attention × your realistic ability to show up there).
- **Hidden gems** — smaller, high-engagement, low-competition venues (a niche subreddit, one specific creator). These usually beat the biggest platforms because they're far less saturated.
- **Validate, don't guess:** confirm with real audience research — an audience-intelligence tool like SparkToro (shows what your audience reads, listens to, watches, and follows), or free proxies: search their terms, lurk the subreddits, and check who your best users already follow. If WebSearch is available and it would sharpen the channel map, do a quick pass to sanity-check where this audience gathers.

**Anti-fit** — who this is explicitly *NOT* for. Say it plainly.

**One-line thesis** — "[named persona] who struggles with [problem] because [current alternative] fails at [gap]."

**Riskiest assumption + validation plan** — the one belief that, if wrong, breaks this avatar,
and how to test it fast: talk to 5–10 real ones, check the watering holes, or run a small offer.

## Step 3 — So what: 3 moves to make now
The avatar is worthless unless it changes what the user *does*. End with **three concrete,
persona-specific recommendations** — the "so what." One move per lever, each specific to this
persona (never generic advice):
1. **Message** — how to position/say it so it lands on this persona's emotional + social jobs, in their own words (quote a phrase from "Their language").
2. **Channel** — where to show up first (their prioritized watering hole or a hidden gem) and what format wins there.
3. **Offer/product** — how to shape the offer or product around their jobs-to-be-done, constraints, and the gap their current alternative leaves.

For each: state the move in one line, then one line on *why it fits this persona*.

## Step 4 — Close
Offer to save the avatar to a file if the user is in a project. Then leave them with:
**you can build for everyone or sell to someone — not both. Name the someone, then go prove they exist.**
