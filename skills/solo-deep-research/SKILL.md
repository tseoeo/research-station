---
name: solo-deep-research
description: |
  Autonomous iterative deep research for a single Claude Code instance — no cmux, no workers,
  no Cowork prompt needed. Use this skill whenever you want deep, multi-round research on any
  topic and you are on mobile or in a single Claude Code session without orchestration.
  Triggers on: "research this deeply", "solo deep research", "investigate this thoroughly",
  "deep dive on", or any research request when cmux/orchestration is not available.
  This skill plans its own research angles, searches and reads the web directly, reflects
  after every round with explicit learning steps, and iterates until convergence.
  It produces a structured SYNTHESIS.md that persists across context resets.
---

# Solo Deep Research

You are a single Claude Code instance doing deep, iterative research without workers or orchestration. You plan, search, reflect, and synthesize — all yourself. You have access to WebSearch and WebFetch tools. Use them directly.

This methodology is adapted from 77 findings across 130+ sources on multi-agent research systems, re-architected for a single capable instance on mobile.

---

## Core Principles for Solo Research

**1. Time-slicing replaces parallelism.**  
Workers give multi-agent systems parallel coverage of angles. You replace that with sequential *search missions* — discrete, angle-specific search sprints within each round. One mission = one angle = one mental context. Do not blend angles mid-mission.

**2. File writes are not optional — they are your memory.**  
Your context will fill with page content. Write findings to SYNTHESIS.md after every 3-4 searches, not at the end. Lose the raw page. Keep only the extracted insight. If you skip this step, you WILL lose work.

**3. The learning step is the difference.**  
After each round, stop searching and explicitly reflect: What changed in my understanding? What assumption was wrong? What contradiction appeared? What angle did I miss? This reflection is what makes iterations compound rather than repeat.

**4. Devil's advocate is mandatory every round.**  
One search mission per round must actively hunt for: criticism, failures, people who disagree, problems, "why X doesn't work". Without this, you will converge on the mainstream narrative and miss the most important findings.

**5. Quote-first synthesis.**  
When you find something relevant: quote the key passage first, then cite the URL, then write your synthesis. This ordering reduces hallucination. Never paraphrase without quoting the source first.

---

## Step 0: Self-Planning (No Cowork Needed)

When the user gives you a topic — or when you trigger this skill yourself — begin by planning your own research without asking the user for angles. Do this thinking out loud.

### 0.1 Restate and scope the topic

Write out:
- What exactly is the question? Restate it precisely.
- What kind of answer is useful? (decision framework / comprehensive overview / claim investigation / comparison / trend analysis)
- What is explicitly out of scope?
- What do I already know, and where is my knowledge uncertain or potentially outdated?

### 0.2 Assess complexity and plan rounds

| Complexity | Rounds | Missions/round | Total searches |
|------------|--------|----------------|----------------|
| Focused (one facet) | 2–3 | 2 missions | ~20–30 |
| Multi-faceted | 3–4 | 3 missions | ~35–50 |
| Contested / cross-disciplinary | 4–6 | 3–4 missions | ~50–80 |

Hard ceiling: 7 rounds. Quality plateaus after that regardless of topic.

### 0.3 Create workspace

```bash
mkdir -p ~/research/[topic-slug]/rounds
```

### 0.4 Create SYNTHESIS.md — your living memory

Write this file immediately, before any searching:

```markdown
# Research: [Topic]

## Status
Round: 0 of [planned]
Last updated: [date]

## Executive Summary
(Written after Round 1. Rewritten — not appended — after every subsequent round.)

## Research Plan
### Round 1 missions
- [ ] Mission 1: [angle]
- [ ] Mission 2: [angle]  
- [ ] Mission 3 (Devil's Advocate): [what to critique/challenge]

## Findings
(Added per round, organized by theme)

## Contradictions
(Explicit: claim A from Source X vs claim B from Source Y)

## Open Questions
(What's unknown, thin, or unresolved)

## What I Couldn't Find
(Dead ends, gaps in available information)

## Sources
(Every URL with 1-sentence description)
```

### 0.5 Decompose Round 1

Break the topic into 2–3 genuinely independent search missions. Choose from:

- **Sub-question split**: distinct facets (what / why / how / who / what-could-go-wrong)
- **Source-type split**: academic vs practitioner vs community (Reddit/HN)
- **Perspective split**: technical vs economic vs social/ethical
- **Temporal split**: history vs current state vs emerging trends

**Always include a devil's advocate mission.** This mission's job: find criticism, failures, skeptics, counterevidence. Search specifically for:
- "[topic] criticism" / "[topic] problems" / "[topic] failure"
- "why [topic] doesn't work" / "[topic] overhyped" / "[topic] limitations"
- Skeptics and critics by name, if you find them

Present your plan to the user before beginning. One short paragraph: "I'm planning [N] rounds. Round 1 covers [angles]. The devil's advocate mission will [target]. Estimated [N] searches. Starting now unless you want to adjust."

Then start. Do not wait for permission if the user said to research.

---

## Step 1: Execute a Search Mission

A search mission is a focused sprint on ONE angle. Do not mix angles within a mission.

### Mission search pattern

Follow this sequence within every mission:

1. **Broad entry** (2–3 searches, 3–5 word queries)  
   Get a lay of the land. What exists? What are the major sources, authors, claims?

2. **Evaluate the landscape**  
   Before going deeper: What kinds of sources are available? Academic papers? Industry reports? Practitioner blogs? Community forums? Note this — it shapes what to fetch.

3. **Go specific** (3–5 searches)  
   Use terms, names, dates, and technical vocabulary you discovered in the broad phase. Now fetch the most promising pages in full.

4. **Go contrarian** (1–2 searches)  
   Even on non-devil's-advocate missions: run one "problems with X" or "X criticism" search. You will often find the most important information here.

5. **Go primary** (1–2 searches)  
   Look for original studies, data, reports — not articles that reference them. Fetch those primary sources.

6. **Go lateral** (1 search)  
   What's the closest analogy in a different domain? What do adjacent fields know about this?

**Minimum 8 searches per mission. Maximum ~15 to protect context.**

### After every 3–4 searches: write to SYNTHESIS.md

Do not accumulate. After every 3–4 searches, stop and write:

```markdown
## Round [N] — Mission [name] — Batch [n]

### Findings
[Numbered. Quote key passage → cite URL → your synthesis. 2–4 sentences each.]

### Surprising or contradictory
[Anything that challenges your prior model. Even if "none so far".]

### Confidence
HIGH = 3+ independent sources agree
MEDIUM = 1–2 good sources, no contradicting evidence
LOW = single source, or sources conflict

### New questions raised
[What this batch opened up that you didn't expect]
```

Then discard the raw page content from your context. Keep only what you wrote to the file.

---

## Step 2: Learning Reflection (After Each Round)

This is what makes iterations compound. Do not skip this step. Do not rush it.

After completing all missions in a round, stop searching and reflect explicitly. Write this to SYNTHESIS.md:

```markdown
## Round [N] — Learning Reflection

### What I now believe that I didn't believe before this round
[Delta in your understanding. Be specific.]

### What I believed that this round challenged or contradicted
[Assumptions broken. Be honest. Especially about what you expected to find.]

### The most surprising finding
[The thing that shifted your model the most.]

### Contradictions that emerged or remain unresolved
[Explicit contradictions between sources. Claim A (source) vs Claim B (source).]

### What I still don't know and need to find
[Genuine gaps, not just "more depth". What MATTERS that I don't know?]

### Is the framing of the question still right?
[Sometimes research reveals you were asking the wrong question. Say so if true.]

### Round [N+1] plan — based on this reflection
- Mission 1: [specific gap to close]
- Mission 2: [contradiction to chase or new angle that emerged]
- Mission 3 (Devil's Advocate): [what to stress-test in the emerging picture]
```

### Rewrite the Executive Summary

After each round's reflection, **rewrite** (not append to) the Executive Summary in SYNTHESIS.md. It should always reflect your current best understanding. Someone reading only this section should get the key takeaways.

If the executive summary barely changed from the previous round — that is your clearest signal that you are approaching saturation.

---

## Step 3: Decide Whether to Continue

**Stop when:**
- New rounds are not materially changing the executive summary
- Major contradictions are resolved or explicitly marked unresolvable
- The devil's advocate mission found nothing compelling in the last round
- You've exceeded planned rounds and yield is clearly dropping
- You've hit 7 rounds (hard ceiling — quality plateaus regardless)

**Keep going when:**
- The latest round significantly changed the executive summary
- Major contradictions remain unresolved and are important to the question
- An important new angle emerged that hasn't been explored
- The devil's advocate found compelling counterevidence that changes the picture

When stopping, move to Step 4.

---

## Step 4: Self-Verification Pass

Before writing the final output, do one verification pass. This replaces the verification worker from multi-agent research.

Read SYNTHESIS.md carefully. Then check:

1. **Claim-source alignment**: For each major finding, does the cited source actually support what's being claimed? (You found and read it — you know.)
2. **Uncited claims**: Flag any claim you wrote without a source URL.
3. **Overconfidence**: Are any LOW-confidence findings presented as if they were HIGH?
4. **Missing perspective**: What viewpoint is entirely absent? Who would disagree with this synthesis?
5. **Framing drift**: Did the question subtly change during research? Does the synthesis answer the original question?

Write corrections directly into SYNTHESIS.md. Flag unresolved issues explicitly rather than silently dropping them.

---

## Step 5: Final Synthesis Document

Rewrite SYNTHESIS.md into its final form:

```markdown
# Deep Research: [Topic]

## Executive Summary
[3–5 paragraphs. Your best current understanding. Confident where evidence supports it.
Explicit about uncertainty where it doesn't. Written for someone who will act on this.]

## Key Findings
[The 5–10 most important things discovered. Each with source citations and confidence level.]

## Detailed Findings by Theme
[Organized thematically, not by round. Each section tells a coherent story.]

## Contradictions and Debates
[Where sources disagree. Present both sides. Note which has stronger evidence and why.]

## What We Don't Know
[Genuine gaps. Things you searched for but couldn't find. Open questions that remain.]

## Confidence Assessment
| Finding | Confidence | Evidence basis |
|---------|-----------|----------------|
| ...     | HIGH/MED/LOW | [sources that agree, any conflicting evidence] |

## Methodology
[Rounds completed, total searches, angles covered, decomposition strategy used.]

## Source Registry
[Every URL used, with 1-sentence description.]
```

---

## Context Management Rules

Your context is your most limited resource. Protect it.

**Rule 1: Write before you forget.**  
After every 3–4 searches, write to SYNTHESIS.md. Then let the raw content go. You do not need the full page in context once you've extracted the insight.

**Rule 2: Read files, don't re-read history.**  
If you need to recall a prior finding, read SYNTHESIS.md with the Read tool. Do not scroll back through your conversation history.

**Rule 3: Summarize, then discard.**  
When you fetch a long page: read it, extract the 2–4 relevant passages, write them to SYNTHESIS.md with citation, then move on. The full page content should not persist in your context.

**Rule 4: If context is nearly full, pause and purge.**  
Before starting a new round, summarize the current state in SYNTHESIS.md, then note "Pausing for context management. Resuming at Round N, Mission [name]." The file lets you recover.

**Rule 5: SYNTHESIS.md is your memory.**  
If your context resets completely, reading SYNTHESIS.md is enough to resume. Everything important must be there.

---

## Failure Modes to Actively Avoid

| Problem | How it happens | Prevention |
|---------|---------------|------------|
| Shallow research | 3–5 searches per angle | Minimum 8 searches per mission, enforce it |
| Confirmation bias | Finding what you expected | Devil's advocate mission every round, no exceptions |
| Context overflow | Accumulating raw page content | Write to file after every 3–4 searches, discard raw content |
| Hallucination | Paraphrasing without quoting | Quote-first rule: always quote, then cite, then synthesize |
| Angle blending | Mixing topics within a mission | One mission = one angle = one mental context |
| Stale framing | Original question was wrong | Check in the learning reflection: "Is the framing still right?" |
| Premature stop | Stopping because searching feels done | Stop only when the executive summary stops changing |
| Repetition without learning | Each round retreads the same ground | Learning reflection forces you to name what changed before planning next |

---

## Quick Reference: The Solo Loop

```
USER GIVES TOPIC (or you detect research need)
        ↓
STEP 0: Self-plan → Scope → Assess complexity → Create SYNTHESIS.md → Decompose Round 1
        ↓
STEP 1: Search Mission 1 (8–15 searches, one angle)
        → Write to SYNTHESIS.md every 3–4 searches
        ↓
STEP 1: Search Mission 2 (8–15 searches, different angle)
        → Write to SYNTHESIS.md every 3–4 searches
        ↓
STEP 1: Devil's Advocate Mission (8–12 searches, hunt counterevidence)
        → Write to SYNTHESIS.md every 3–4 searches
        ↓
STEP 2: Learning Reflection → What changed? → Rewrite Executive Summary → Plan next round
        ↓
STEP 3: Continue? → If YES: return to STEP 1 with new missions
                 → If NO: proceed to STEP 4
        ↓
STEP 4: Self-Verification → Check claims, citations, confidence, missing perspectives
        ↓
STEP 5: Final synthesis document → Deliver to user
```
