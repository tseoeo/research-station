# Research Station

A workspace for deep research projects. Each project is a self-contained folder with everything from initial brief to final output.

---

## How It Works

Research station is where ideas get investigated thoroughly before becoming anything else (essay, talk, book, framework, etc.). The process typically goes:

1. **Plan** — discuss the topic in Cowork, clarify scope and angles
2. **Brief** — write a structured BRIEF.md that defines what we're looking for
3. **Research** — hand off to the Claude Code multi-agent orchestrator, which runs workers to search, read, and synthesize
4. **Distill** — back in Cowork, turn raw research into structured distillations (one per concept/angle)
5. **Narrate** — build the practical narrative: working notes that put the thinking in the author's voice, enriched with references
6. **Iterate** — go deeper on specific threads, challenge assumptions, fill gaps

---

## Folder Structure

```
research station/
├── README.md                          ← you are here
├── [project-slug]/                    ← one folder per research project
│   ├── BRIEF.md                       ← the research brief (what we're looking for)
│   ├── angle1-[name].md               ← raw research output per angle (from workers)
│   ├── angle2-[name].md
│   ├── ...
│   ├── [topic]-distillation.md        ← structured distillation of a concept
│   ├── practical-narrative.md         ← working notes in the author's voice
│   └── ...                            ← any other artifacts (tables, drafts, etc.)
```

Each project folder is **self-contained** — it holds everything from the initial brief through raw research through distilled thinking through working drafts. Nothing lives outside its folder.

---

## Naming Conventions

- **Project folders**: lowercase, hyphenated, descriptive (`ai-as-multiplier-not-mind`, `future-of-work-policy`, `open-source-economics`)
- **BRIEF.md**: always uppercase, always the starting point
- **Angle files**: `angle[N]-[short-name].md` — raw research output from workers
- **Distillations**: `[topic]-distillation.md` — structured breakdowns of individual concepts
- **Narrative**: `practical-narrative.md` — the working notes file where the author's thinking lives

---

## Principles

- **Research first, form later.** Don't decide if something is an essay or a book or a talk until the thinking is mature. Start with notes.
- **Structure findings, don't just list them.** Every piece of research should be categorized: supporting, challenging, adjacent, or expanding. This forces engagement, not just collection.
- **Enrich references.** Never just name-drop. Every reference mentioned in working notes gets a short explanation of what that person actually said and why it matters.
- **Track what's missing.** Gaps and silences are as important as findings. Every research project should have an explicit "what are we missing" thread.
- **Keep it self-contained.** If someone opens a project folder cold, they should be able to understand what the research is about, what was found, and where the thinking currently stands.
