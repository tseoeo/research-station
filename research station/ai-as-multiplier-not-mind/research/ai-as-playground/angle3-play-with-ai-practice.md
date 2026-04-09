# Angle 3: Play With AI Specifically — Emerging Practice and What Works

**Core question:** What does productive play with AI actually look like in practice? What distinguishes play that builds skill from play that wastes time or reinforces the enchantment?

**Research date:** April 2026
**Status:** Structured landscape for essay development

---

## Table of Contents

1. [Supporting: Play Modes That Work](#1-supporting-play-modes-that-work)
2. [Supporting: The Practitioner-Tinkerers](#2-supporting-the-practitioner-tinkerers)
3. [The Vibe Coding Phenomenon — Play and Its Limits](#3-the-vibe-coding-phenomenon--play-and-its-limits)
4. [The Prompt Engineering Community as Play Community](#4-the-prompt-engineering-community-as-play-community)
5. [Creative Misuse as Epistemic Practice](#5-creative-misuse-as-epistemic-practice)
6. [AI Literacy Through Experimentation — Academic Evidence](#6-ai-literacy-through-experimentation--academic-evidence)
7. [Challenging: When Play Fails](#7-challenging-when-play-fails)
8. [Challenging: The Skill Atrophy Concern](#8-challenging-the-skill-atrophy-concern)
9. [Expanding: How Play Connects to the Three-Part Framework](#9-expanding-how-play-connects-to-the-three-part-framework)
10. [Expanding: Organizational Resistance to Play](#10-expanding-organizational-resistance-to-play)
11. [Noted Gaps](#11-noted-gaps)
12. [Source Index](#12-source-index)

---

## 1. Supporting: Play Modes That Work

The strongest empirical evidence for productive AI play comes from the BCG field experiment and Mollick's subsequent analysis. These identify specific patterns of engagement — and show that the *mode* of interaction matters more than whether AI is used at all.

### 1.1 The BCG Study — Cyborgs, Centaurs, and Self-Automators

**Dell'Acqua, McFowland III, Mollick, Lifshitz-Assaf, Kellogg, Rajendran, Krayer, Candelon & Lakhani, "Navigating the Jagged Technological Frontier" (HBS Working Paper 24-013, September 2023; published Organization Science, 2025)**
A randomized controlled experiment with 758 Boston Consulting Group consultants performing realistic consulting tasks with and without GPT-4 access. Consultants using AI completed 12.2% more tasks, 25.1% faster, and produced results 40% higher quality than the control group — for tasks *inside* the AI's capability frontier. For tasks outside the frontier, AI users performed *worse* than those working without AI. The frontier was "jagged" — irregular, unpredictable, not mapping onto human intuitions about task difficulty.

The study identified two dominant integration strategies:

- **Centaurs** maintained a clear division of labor — strategically delegating some subtasks to AI while retaining others for themselves. Clean handoffs between human and machine work with identifiable boundaries.

- **Cyborgs** deeply intertwined their work with AI in a continuous, iterative flow. Rather than cleanly dividing tasks, they engaged in ongoing back-and-forth dialogue with the AI, weaving AI output into their thinking and vice versa. The boundary between human and machine contribution was blurred.

A third pattern — users who delegated tasks wholesale, submitting prompts and accepting outputs with minimal review — produced significantly worse results, sometimes below the no-AI control group. Mollick has subsequently described this as the **Self-Automator** pattern in talks and in *Co-Intelligence*.

**Why this matters here:** The Cyborg pattern *is* a form of structured play with a tool, whether or not the participants would use that word. It is exploratory (trying things, seeing what happens), iterative (each exchange builds on the last), responsive (the user genuinely reacts to what the AI produces rather than consuming it passively), and intrinsically engaged (the back-and-forth has a quality of curiosity and experimentation, not mechanical task completion). The Self-Automator pattern is the opposite — delegation without engagement, handing work to the tool and walking away. The study provides the strongest experimental evidence that play-as-engagement works and delegation-without-play fails.

### 1.2 Why Self-Automation Fails

The Self-Automator pattern fails through several reinforcing mechanisms:

- **Skill atrophy.** When you stop doing the cognitive work, you lose the ability to evaluate whether the AI's output is good. You can't catch errors you no longer understand. This creates a vicious cycle — the less you engage, the less capable you become of engaging.
- **Invisible frontier-crossing.** The jagged frontier means AI is excellent at some things and terrible at others, but the boundaries are non-obvious. Only someone actively engaged can detect when they've crossed from AI-competent territory to AI-incompetent territory.
- **Loss of domain expertise.** Consultants who delegated heavily produced lower-quality output specifically because they stopped applying their own consulting expertise to structure problems, evaluate logic, and catch domain-specific errors.
- **Illusory competence.** Delegators often *believed* their output was good because the AI produced fluent, professional-sounding text. The gap between perceived and actual quality is the core danger.

Mollick's term for this is **"falling asleep at the wheel"** — automation complacency where the human monitor stops monitoring because the system seems to be working fine, until it catastrophically isn't.

### 1.3 The METR Study — Confidence Without Capability

**METR (Model Evaluation & Threat Research), "Measuring the Impact of AI on Experienced Open-Source Developer Productivity" (February/March 2025)**
Experienced open-source developers were given real tasks on repositories they knew well, randomly assigned to AI-assisted or unassisted conditions. Developers using AI tools (including Cursor, Copilot, and similar) were approximately **19% slower** on average at completing tasks. Crucially, these same developers **predicted they would be 20-24% faster** with AI before seeing their results. Even after completing tasks, they still believed AI had helped.

METR is an AI safety research organization (formerly ARC Evals). The study used a rigorous randomized controlled design with experienced developers working on their own familiar codebases, and objective time measurement.

**Why this matters here:** The METR study demonstrates that "using AI" is not automatically productive. The *mode* of engagement determines whether AI helps or hurts. Fluent AI output creates an *illusion of productivity* — the experience of using AI feels efficient even when it isn't. For complex, familiar tasks, the overhead of managing AI (reviewing output, fixing errors, context-switching) can exceed the time saved. Confidence in AI's helpfulness is not a reliable indicator of actual benefit. This is multiplication of confidence without multiplication of capability — and it directly parallels the Self-Automator problem. Combined with the BCG study, the picture is clear: iterative, engaged use (Cyborg/play mode) works; passive delegation can make you slower *and* worse while making you *feel* faster *and* better.

---

## 2. Supporting: The Practitioner-Tinkerers

### 2.1 Ethan Mollick — The Case for Learning by Doing

**Mollick, E., *Co-Intelligence: Living and Working with AI* (Portfolio/Penguin, April 2024)**
Mollick's core practical argument: try using AI for every task for a sustained period — not because it will help with everything, but because this is the only way to learn where it helps and where it doesn't. The learning is experiential, not theoretical.

Key arguments relevant to the play thesis:

- **"Invite AI to everything."** Mollick's signature advice. Use AI for unexpected tasks, push it until it breaks, develop calibrated intuitions through experience. The learning is anti-prescriptive — he resists formulas and emphasizes that the technology changes too fast, the capabilities are too context-dependent, and the skill is fundamentally *tacit*.
- **The impossibility of expertise through instruction.** You cannot learn to use AI well by reading prompt engineering guides or best-practice documents. The skill develops through doing.
- **Experimentation as the core AI skill.** The most important skill is willingness to experiment — trying AI on unexpected tasks, pushing its limits, learning its failure modes through experience. People who play develop genuine capability. People who follow scripts don't.
- **The "secret cyborg" problem.** Many knowledge workers are already using AI but hiding it from employers and colleagues. This creates an invisible transformation of work with no institutional learning or governance.

**Mollick, E., "One Useful Thing" (Substack, 2023-present, oneusefulthing.substack.com)**
Mollick's blog models the Cyborg approach in practice — he constantly probes new AI models on real tasks, tests edge cases, compares outputs, and publishes what he learns. The methodology *is* the message. Key recurring themes:

- Prompt engineering as a fixed skill set is largely a myth; what matters is iterative, responsive engagement.
- Banning AI teaches nothing; requiring people to use AI *and reflect on the process* teaches real skills.
- The "just use it more" advice, refined over time to acknowledge that experience without reflection can entrench misconceptions.

**Mollick & Mollick, "Assigning AI: Seven Approaches for Students, with Prompts" (Wharton Working Paper / SSRN, 2023-2024)**
Ethan and Lilach Mollick propose structured ways to integrate AI into coursework. Several approaches are explicitly experimental — having students test AI capabilities, find failure modes, compare AI output to their own work. The implicit pedagogy is learning-through-doing — a structured form of play.

### 2.2 Simon Willison — Building to Understand

**Simon Willison (simonwillison.net, 2023-2025)**
Creator of Datasette, co-creator of Django. Willison has become one of the most prolific and influential voices on practical AI literacy. His core thesis: **the only way to develop reliable intuitions about LLMs is to build things with them and systematically probe their behavior.**

Key arguments and pieces:

- **"Things we learned about LLMs in 2024"** (simonwillison.net, late 2024). Many "facts" about LLMs from early 2023 turned out to be wrong, and only people who kept experimenting updated their mental models. AI literacy is not a fixed body of knowledge but an ongoing practice of experimentation because the tools change rapidly.
- **The "not all AI-assisted programming is vibe coding" distinction** (early 2025). Willison drew a sharp line between vibe coding (accepting code you do not understand) and AI-assisted coding (using AI to generate code you then review, test, and understand). Conflating the two is dangerous because it lets people dismiss legitimate AI-assisted development or think vibe coding is sufficient for production work.
- **Prompt injection work (2023-2024).** Willison's understanding of prompt injection as a fundamental unsolved problem came entirely through building and testing systems — he discovered the contours of the problem by tinkering, not by reading papers. A case study in how experimentation yields insights theory does not.
- **The "TIL" and tool-building approach.** Willison publishes small experiments constantly — building CLI tools (llm, shot-scraper, etc.), testing new models on release day, documenting what works and fails. His implicit pedagogy: AI literacy develops through a cycle of hypothesis-experiment-document.

Willison treats LLMs as a new kind of material to be understood empirically. He pushes back against people who either refuse to engage ("it's all hype") or who accept outputs uncritically ("AI will replace developers"). Systematic tinkering produces a calibrated understanding that neither extreme achieves.

### 2.3 Maggie Appleton — Designing for Tinkering

**Maggie Appleton (maggieappleton.com, 2023-2025)**
Designer, anthropologist, and developer. Appleton's work is fundamentally about the gap between how people *actually* interact with AI and how the interfaces *assume* they will.

- **"The Expanding Dark Forest and Generative AI"** (maggieappleton.com, 2023). As AI-generated content floods the internet, developing taste and discrimination about AI output requires extensive personal experience with generating it. You need to have played with these tools to recognize their outputs.
- **"Language Model Sketchbook"** and alternative interface explorations (2023-2024). The chatbot interface (a single text box) is a deeply impoverished way to interact with language models. It constrains what people can discover about AI capabilities. Appleton advocates for interfaces that make the model's behavior more visible, manipulable, and explorable.
- **"Folk interfaces"** — the informal, creative ways people interact with AI that diverge from designer intentions. Appleton documents and celebrates the ways ordinary users tinker with AI interfaces, connecting directly to the creative misuse theme.
- **The "taxi for the mind" critique.** AI should be a "bicycle for the mind" (Steve Jobs's metaphor), but current interfaces make it more like a "taxi for the mind" — you tell it where to go and passively receive the output. Better interfaces would enable more active exploration and tinkering. This aligns with Papert's constructionism — you learn best by building things, and the interface should support construction, not just conversation.

**Why Appleton matters here:** Her critique is that the *interface* constrains the *play*. The chat paradigm encourages delegation (type a question, get an answer) rather than exploration (manipulate, compare, iterate, shape). If play is the right mode for learning AI, then the interfaces need to be redesigned to support play — not just query-response.

---

## 3. The Vibe Coding Phenomenon — Play and Its Limits

### 3.1 Origin and Definition

**Andrej Karpathy, X post (February 2, 2025)**
Karpathy — formerly of OpenAI and Tesla's AI division — coined "vibe coding" to describe a new way of programming: "fully give in to the vibes, embrace exponentials, and forget that the code even exists." The workflow: speak to an LLM in natural language, accept whatever code it produces, run it, iterate based on whether the output looks right — without reading or deeply understanding the generated code. Karpathy explicitly noted this was suitable for throwaway or personal projects: "the bar is that it works."

The term went viral immediately and became the dominant shorthand for this style of AI-assisted development.

### 3.2 The Speed-Quality Tradeoff

The "10-100x creation, 0.4-0.6x quality" formulation circulates widely in practitioner discourse but does not trace to a single peer-reviewed study. It is a community heuristic — directionally supported by evidence but not precisely measured.

**On the speed multiplier (10-100x):**
- Anecdotal practitioner reports are the primary source. Many developers reported shipping functional prototypes in hours rather than weeks.
- **McKinsey & Company (June 2023)** found roughly 30-50% faster task completion for well-defined coding tasks with AI assistance — far more modest than "100x" but covering traditional AI-assisted coding, not full vibe coding.
- **Google internal studies (2024)** reportedly found approximately 30% faster task completion with AI assistance.
- The "100x" figure likely applies to a specific scenario: a non-programmer building something from zero that they otherwise *could not have built at all*. The multiplier is arguably infinite in that case, and "100x" is a rough heuristic for "went from impossible to possible."

**On the quality discount (0.4-0.6x):**
- **GitClear, "Coding on Copilot: 2023 Data Suggests Downward Pressure on Code Quality" (January 2024).** Analyzed code churn data across AI-assisted projects. AI-assisted code had significantly higher churn rates (code written and then quickly revised or reverted), suggesting lower initial quality.
- **Uplevel Engineering Productivity Study (2024).** Examined teams using GitHub Copilot and found no statistically significant improvement in pull request cycle time, while bug rates appeared to **increase by 41%** in some cohorts.
- The quality discount captures a widely observed phenomenon: vibe-coded output is functional but brittle — it works for the happy path but has poor error handling, security vulnerabilities, no tests, inconsistent architecture, and hidden bugs.

**Bottom line:** The speed gains are real but context-dependent; the quality discount is real and possibly understated for complex systems. The specific figures should be treated as community heuristics, not measured statistics.

### 3.3 Vibe Coding as Play

The practitioner community consistently describes vibe coding using language associated with play, exploration, and creative flow:

- **Low stakes, high iteration speed.** Code generates in seconds; the cost of trying something and throwing it away is near zero. Multiple practitioners describe "just asking for something wild to see what happens." This matches Caillois's *ludus* — structured play with loose goals and exploratory process.
- **Conversational and improvisational.** The interaction pattern — describe, generate, observe, redirect — resembles improvised conversation more than traditional engineering. Developers describe it as "jamming" or "sketching."
- **The "Bob Ross effect."** Several commentators noted vibe coding feels like following along with a painting tutorial — you describe the happy little trees and they appear. The satisfaction comes from seeing results materialize, not from craftsmanship of the underlying code.
- **Accessible to non-experts.** A significant part of the "play" framing comes from people who are *not* professional developers — designers, product managers, writers — who can now build functional tools. For them, the entire experience is novel and exploratory.

**Pieter Levels (@levelsio, 2025)** — indie hacker — became a prominent example of vibe coding in practice, reportedly building and shipping multiple functional web applications almost entirely through AI code generation. Demonstrated the approach's viability for solo entrepreneurs building MVPs and revenue-generating products.

### 3.4 The Limits — Critical Voices

**Simon Willison, "Not all AI-assisted programming is vibe coding" (simonwillison.net, early 2025)**
The sharpest distinction in the discourse. Vibe coding is fine for disposable scripts and personal tools, but the moment code needs to be maintained, secured, or debugged, the practitioner must actually understand what was generated. Core concern: the **maintenance and debugging problem** — when vibe-coded software breaks, the person who built it often cannot fix it because they never understood it.

**Kelsey Hightower (X posts, early 2025)**
Former principal engineer at Google. Skepticism centered on the idea that **software engineering is not just writing code — it is understanding systems.** Vibe coding produces artifacts without understanding. Analogy: the difference between driving a car and understanding how an engine works — fine until the engine breaks down on a remote road.

**Security concerns (multiple researchers, early 2025):**
Vibe-coded applications deployed with serious vulnerabilities: SQL injection, hardcoded secrets, missing authentication checks, insecure default configurations, deprecated dependencies. Because practitioners do not review generated code, the entire OWASP Top 10 becomes a live threat. Security community discussions in early 2025 began treating "LLM-generated code without review" as an emerging threat vector.

**The "it works until it doesn't" problem:**
Vibe-coded software tends to work for the demo case but fails on edge cases, under load, with unexpected input, or when requirements change. Critics call this **"demo-driven development"** — code optimized to pass the immediate visual check, not to be robust. The deeper version: when the practitioner does not understand the code, they cannot reason about failure modes, extend it predictably, or debug it in production. The codebase becomes a black box that happens to produce the right output — until it doesn't.

### 3.5 Vibe Coding and the Jagged Frontier

The jagged frontier framework maps directly onto the vibe coding experience:

- **Inside the frontier:** Building a standard CRUD app, a personal dashboard, a static site, a simple API wrapper, a data visualization script. Well-represented in training data, clear patterns. Vibe coding works beautifully — hence the "10-100x" feeling.
- **Outside the frontier:** Complex state management, novel algorithmic problems, security-critical authentication flows, performance optimization, subtle concurrency bugs, domain-specific business logic with unusual edge cases. Vibe coding produces code that *looks* correct but is subtly wrong — and the practitioner, having not read the code, cannot detect the failure.
- **The danger zone:** The frontier is jagged, meaning you cross it *without knowing you have crossed it*. A vibe coder building a web app might be inside the frontier for 95% of the project and then unknowingly cross outside it for the critical 5% — the payment processing logic, the access control system. Because the workflow involves not reading the code, this crossing is invisible.

**Why vibe coding matters for the play argument:** Vibe coding is play *without judgment*. It captures the exploratory, low-stakes, iterative qualities of play but strips out the evaluative component. Vibe coders are not reflecting on what works and what doesn't — they are accepting results based on vibes, not building calibrated mental models. Vibe coding is what happens when play loses its reflective dimension. It demonstrates both the power and the danger: play-as-exploration can create extraordinary things, but play-without-evaluation creates fragile things that the creator cannot maintain or understand.

---

## 4. The Prompt Engineering Community as Play Community

### 4.1 What Works — Evidence-Backed Techniques

- **Wei et al., "Chain-of-Thought Prompting Elicits Reasoning in Large Language Models" (NeurIPS 2022).** Asking models to show reasoning steps significantly improves performance on math and logic tasks. One of the most robustly replicated findings in prompt engineering research.
- **Brown et al., "Language Models are Few-Shot Learners" (NeurIPS 2020).** The original GPT-3 paper established that providing examples in-context meaningfully steers output. Well-supported and consistently useful.
- **Structured output formats.** Asking for specific formats (JSON, markdown, numbered lists) reliably shapes outputs. Documented across vendor documentation and practitioner experience.

### 4.2 What's Cargo Cult

- **"Jailbreak" prompts treated as stable techniques.** Prompts like "DAN" (Do Anything Now) are shared as if they are reliable tools, but they break with each model update. Ritualistic behavior — copying exact phrasings without understanding why they sometimes work.
- **Emotional manipulation prompts.** "Take a deep breath," "I'll tip you $200," etc. Some showed marginal effects in specific benchmarks (a Google DeepMind paper found "take a deep breath" slightly helped on GSM8K math), but wildly overgeneralized into superstitious practices applied indiscriminately.
- **Elaborate persona prompts.** Multi-paragraph character backstories ("You are an expert senior developer with 20 years of experience who...") are largely performative beyond a certain point. The useful signal is task specification, not character fiction.

### 4.3 Critical Voices on Prompt Engineering

**Ethan Mollick (OneUsefulThing, 2023-2024)**
Prompt engineering as a specialized skill is largely a myth. Most gains come from clear communication and domain knowledge. It is closer to "learning to write a good email to a smart intern" than to programming.

**Narayanan & Kapoor, *AI Snake Oil* (Princeton University Press, 2024)**
Critique the broader ecosystem of AI expertise claims, including prompt engineering as a durable technical skill. Much of what passes for prompt engineering expertise is non-reproducible across model versions and represents a poor foundation for AI literacy.

**Elvis Saravia / DAIR.AI, "Prompt Engineering Guide" (ongoing, GitHub)**
Attempts to separate empirically validated techniques from folklore. Useful as documentation of what the community believes works, with varying evidence levels.

**Lilian Weng, "Prompt Engineering" (lilianweng.github.io, 2023)**
A technically rigorous survey from an OpenAI researcher that grounds prompt engineering in actual research papers. Implicitly critiques the gap between what research supports and what practitioners claim.

**Riley Goodside (Scale AI, 2022-2024)**
One of the earliest "prompt engineers" (hired by Scale AI with that title in 2022). Early work demonstrated genuine discoveries about model capabilities through systematic experimentation — essentially a tinkering/play approach. Over time, shifted toward acknowledging that many prompt tricks are model-specific and ephemeral. His trajectory illustrates the tension between prompt engineering as exploration (generative, play-like) and as fixed technique (brittle, cargo cult).

**Why prompt engineering matters for the play argument:** The prompt engineering community is a natural experiment in what happens when large numbers of people play with a tool simultaneously. The results are mixed: some genuinely useful techniques emerged (chain-of-thought, few-shot), but much of the community developed cargo cult practices — rituals that feel like skill but do not transfer across model versions. The difference tracks the play-vs-game distinction: genuine exploration that responds to what the tool actually does (play) produces lasting insight; following scripts that worked once (games with fixed rules) produces fragile techniques that break when the tool changes.

---

## 5. Creative Misuse as Epistemic Practice

Using AI for things it wasn't designed for is one of the most productive forms of play, because it reveals design assumptions and hidden capabilities that conventional use never surfaces.

### 5.1 Theoretical Grounding

**Dourish, Paul, "The Appropriation of Interactive Technologies" (various publications, 2003 onward)**
Dourish's HCI work on technology appropriation — users adapting tools for unintended purposes — argues that appropriation is not aberrant but is how technology becomes meaningful in practice. Tools gain their real significance through use patterns their designers never imagined.

**Hertz & Parikka, "Zombie Media: Circuit Bending, Media Archaeology, and Techno-Logical Un-Dead" (Leonardo Journal, MIT Press, 2012)**
Theorize "zombie media" and circuit bending as ways of understanding technology through intentional misuse. The framework applies directly to AI: using tools against their intended grain reveals what the designers assumed and what the system actually encodes.

### 5.2 AI-Specific Creative Misuse

**Janelle Shane, *You Look Like a Thing and I Love You* (Voracious/Little Brown, 2019) and AI Weirdness (aiweirdness.com, ongoing through 2025)**
Shane systematically explores AI systems by giving them unusual tasks — neural networks generating paint colors, recipes, names. Explicitly framed as play that reveals how systems actually work. Her key argument: **the errors and weird outputs are more informative than the successes** for understanding AI capabilities. Textbook case of creative misuse as epistemic practice.

**Holly Herndon and Mat Dryhurst (various works and interviews, 2019-2024)**
Musicians who used AI (particularly voice cloning and generative audio) in deliberately transgressive ways. Herndon's album *PROTO* (2019) and subsequent work with her AI "baby" Holly+ used AI as a creative collaborator. Their argument: artists pushing AI into unintended territory are doing essential R&D that companies building these tools cannot or will not do.

**Adversarial collaboration and jailbreaking as creative misuse:**
AI safety researchers have noted that jailbreaking and red-teaming are forms of creative misuse that generate genuine knowledge about model capabilities. Anthropic, OpenAI, and others formalized this through red-team programs, but the spontaneous community versions (jailbreak communities, prompt injection researchers like Willison) represent organic creative misuse that often discovers capabilities and limitations before formal evaluation does.

**Why creative misuse matters here:** Creative misuse treats AI as a toy rather than a tool. In Huizinga's framework, play is activity within defined boundaries that generates knowledge through experimentation. The boundaries are the model's capabilities and safety guardrails; the "play" is systematically exploring what happens when you push against them. The key insight: playful misuse often discovers capabilities and limitations before formal evaluation does, because the misusers are exploring territory the designers didn't think to test.

---

## 6. AI Literacy Through Experimentation — Academic Evidence

### 6.1 HCI and Learning Sciences

**Zamfirescu-Pereira, Wong, Hartmann & Yang, "Why Johnny Can't Prompt: How Non-AI-Experts Try (and Fail) to Design LLM Prompts" (CHI 2023, ACM)**
Observed non-experts attempting to use LLMs. People's mental models of AI were often wildly inaccurate, and they improved primarily through trial and error rather than through reading instructions. Key finding: people who experimented more developed better (though still imperfect) mental models. Directly supports the experimentation thesis.

**Tankelevitch et al., "The Metacognitive Demands and Opportunities of Generative AI" (CHI 2024, ACM)**
Interacting with generative AI requires and develops metacognitive skills — users must constantly evaluate, calibrate, and adjust. Effective AI use is essentially a metacognitive practice that develops through experience, not instruction alone.

**Long & Magerko, "What is AI Literacy? Competencies and Design Considerations" (CHI 2020, ACM)**
An influential framework defining AI literacy competencies. Predates the LLM era but established that AI literacy includes both conceptual understanding and practical skills, and that practical skills are best developed through hands-on interaction. Subsequent research has reinforced this finding.

**Kazemitabaar et al., "Studying the Effect of AI Code Generators on Supporting Novice Learners in Introductory Programming" (CHI 2023)**
Novice programmers who used AI code generators with scaffolded experimentation (guided tinkering) developed better mental models than those who either avoided AI or used it uncritically. Argues for a middle path between prohibition and unrestricted use.

**Denny et al., "Promptly: Using Prompt Problems to Teach Learners How to Effectively Utilize AI Code Generators" (various education venues, 2023-2024)**
Teaching students to use AI code generators through structured "prompt problems" — gamified experimentation. Found structured tinkering more effective than lecture-based instruction for developing practical AI skills.

### 6.2 The "Just Use It" Debate

**The proponents:**
Mollick is the most prominent academic voice: use AI for everything, push it until it breaks, develop calibrated intuitions through experience. Karpathy's vibe coding is the extreme version. The general learning science literature on experiential learning (Kolb, 1984; Papert, 1980) supports the idea that hands-on practice is essential for developing practical skills.

**The critics:**

**Emily Bender (University of Washington, various talks and papers, 2023-2025)**
Without understanding what LLMs are (statistical models of text, not reasoning engines), extensive use can build false confidence rather than genuine literacy. "Just use it" is insufficient and potentially harmful advice. Grounded in the theoretical framework of the "Stochastic Parrots" paper (Bender, Gebru et al., FAccT 2021).

**Narayanan (Princeton, *AI Snake Oil*, 2024)**
Individual tinkering produces anecdotal evidence subject to all the usual cognitive biases (confirmation bias, anchoring, narrative fallacy). Personal experience should be complemented with empirical literacy — understanding benchmarks, evaluations, and the research literature.

**Gebru (DAIR Institute) and the broader AI ethics community**
The "just use it" framing ignores power dynamics, environmental costs, and labor exploitation embedded in AI systems. Focusing on individual experimentation as the path to AI literacy obscures structural questions that cannot be discovered through personal tinkering.

**McQuillan, Dan, *Resisting AI: An Anti-Fascist Approach to Artificial Intelligence* (Bristol University Press, 2022)**
Individual-level "literacy" frameworks are inadequate for understanding AI's societal impacts. The strongest version of the structural critique: play teaches you about the tool but not about the system the tool is embedded in.

### 6.3 The Emerging Synthesis

The emerging consensus (as of early 2025): extensive personal use is necessary but not sufficient. The most effective approaches combine hands-on experimentation with conceptual frameworks, critical evaluation skills, and awareness of limitations and societal context. This is the position Mollick himself has moved toward in his more nuanced writing.

**The folk theory problem:**

**Eslami et al. (CHI 2016, on algorithmic folk theories)**
Extensive use of systems can produce confident but inaccurate mental models. Experience without frameworks can entrench misconceptions. This is the best evidence against pure "just use it" — tinkering without reflection can produce *more* confidence without *more* accuracy.

---

## 7. Challenging: When Play Fails

### 7.1 Play as Avoidance

**Steel, Piers, "The Nature of Procrastination: A Meta-Analytic and Theoretical Review" (Psychological Bulletin 133(1), 2007)**
Task aversiveness is a primary driver of procrastination. When real work is difficult or ambiguous, people gravitate toward adjacent activities that feel productive but avoid the core challenge. Exploratory play with a novel tool fits this pattern: it generates a feeling of learning while deferring the harder question of whether the tool actually improves the work that matters. Steel calls this "productive procrastination" — doing real things, just not the right things.

**Vallerand et al. (Educational and Psychological Measurement, 1992; and later work on harmonious vs. obsessive passion, 2003, 2010)**
Harmonious passion integrates activity with broader goals; obsessive passion lets activity control the person. Applied to AI: harmonious play serves the user's broader goals; obsessive play becomes compulsive tinkering that displaces productive work. The distinction: does AI experimentation serve your actual work or become an end in itself?

**Amabile, Teresa, "The Social Psychology of Creativity" (Springer-Verlag, 1983); and Amabile & Pratt (Research in Organizational Behavior 36, 2016)**
Exploratory behavior is productive only when paired with domain expertise and task motivation directed at a meaningful problem. Play in the absence of domain grounding produces novelty without value. This maps directly to the Self-Automator pattern: exploration without domain engagement produces neither AI skills nor domain skills.

**March, James G., "Exploration and Exploitation in Organizational Learning" (Organization Science 2(1), 1991)**
While organizations tend to under-explore, individuals can *over*-explore. Excessive exploration produces "failure traps" — cycling through new approaches without developing proficiency in any. The individual equivalent is play without calibration: constantly experimenting with AI without building stable workflows that produce reliable value.

### 7.2 Play That Reinforces Enchantment

**Nickerson, Raymond S., "Confirmation Bias: A Ubiquitous Phenomenon in Many Guises" (Review of General Psychology 2(2), 1998)**
Confirmation bias operates most powerfully when people are actively exploring a hypothesis they find appealing. If a user plays with AI expecting impressive results, they will selectively notice the impressive outputs and discount the failures. Play under a prior of "this is amazing" becomes a confirmation machine. The enchantment deepens precisely because the user feels they have tested the tool — they played with it, and it confirmed their expectations.

**Einhorn & Hogarth, "Confidence in Judgment: Persistence of the Illusion of Validity" (Psychological Review 85(5), 1978)**
In environments with poor feedback structures, experience does not improve judgment — it entrenches initial impressions. AI interaction is a poor feedback environment: the tool produces fluent output regardless of correctness, and the user often lacks the means to verify without significant effort. Play in this environment can build false confidence rather than genuine calibration. Experience without reliable feedback produces the illusion of learning.

**Klein, Gary, "Performing a Project Premortem" (HBR, September 2007); and "Sources of Power" (MIT Press, 1998)**
People develop calibration through encountering failures under conditions where the failure is salient and consequential. Low-stakes play, by definition, reduces the salience and consequence of failure. If AI produces a bad output during play, the user may shrug and try again — learning nothing about the frontier. Unstructured play does not force attention to failure modes in the way that real-stakes work does.

**Fogg, B.J., "Persuasive Technology" (Morgan Kaufmann, 2003)**
Repeated positive interactions build "trust momentum." Each impressive AI output during play deposits into a trust account. When the user later encounters a task where AI fails, the accumulated trust makes them less likely to notice or accept the failure. Play that primarily generates positive experiences builds overtrust rather than calibration.

**Moore & Healy, "The Trouble with Overconfidence" (Psychological Review 115(2), 2008)**
Three types of overconfidence: overestimation (thinking you're better than you are), overplacement (thinking you're better than others), and overprecision (being too certain of your estimates). AI play can produce all three: users overestimate their skill at using AI based on a few impressive results, overplace themselves relative to non-users, and become overprecise about where AI works and doesn't based on a narrow sample. Maps directly to the METR finding.

### 7.3 What Productive Play Requires — Boundaries

**Ericsson, Krampe & Tesch-Romer, "The Role of Deliberate Practice in the Acquisition of Expert Performance" (Psychological Review 100(3), 1993)**
Deliberate practice requires clear goals, immediate feedback, and focus on areas of weakness. Play and deliberate practice are not opposed but sequential: play identifies the territory (what's possible, what's interesting, where the edges are), and deliberate practice develops reliable skill within that territory. Without the transition from play to practice, you remain a perpetual beginner who has seen the landscape but mastered none of it. Applied to AI: play discovers the jagged frontier; deliberate practice builds reliable workflows within the zones where AI actually helps.

**Papert, Seymour, *Mindstorms: Children, Computers, and Powerful Ideas* (Basic Books, 1980)**
Learning happens through building in a "microworld" — a constrained environment where experimentation has visible consequences. The constraint is crucial. Unlimited play produces scattered experience. A well-designed microworld focuses play toward productive discovery. Applied to AI: productive play requires constraints — a specific task, a domain you know well enough to evaluate output, a question you're trying to answer. "Just play around with ChatGPT" is not a microworld. "Use ChatGPT to draft five versions of this paragraph and evaluate which captures the argument best" is.

**Csikszentmihalyi, Mihaly, *Flow* (Harper & Row, 1990)**
The productive zone is between boredom (task too easy) and anxiety (task too hard). Productive AI play occupies this zone: tasks challenging enough to reveal the tool's limits but not so complex that the user can't evaluate the output. If someone plays with AI on tasks they don't understand well enough to judge, they get neither learning nor flow — just enchantment.

**Schon, Donald, *The Reflective Practitioner* (Basic Books, 1983)**
"Reflection-in-action" — the expert mode of simultaneously doing and evaluating. Productive play requires this reflective stance: not just generating outputs but actively evaluating them, noticing patterns, building mental models of where the tool succeeds and fails. This contrasts with "technical rationality" (follow the rules) — productive AI use cannot be reduced to best practices or prompt templates. It requires the reflective practitioner's stance of continuous experimental evaluation.

**Bjork, Robert, "Desirable Difficulties in Learning" (Encyclopedia of the Sciences of Learning, Springer, 2012)**
Conditions that slow performance during learning often enhance long-term retention and transfer. Making AI exploration harder — requiring the user to evaluate outputs, compare them to their own work, explain why an output is wrong — produces better calibration than frictionless play. Connects to Bucinca's "cognitive forcing functions": the friction is the feature, not the bug.

---

## 8. Challenging: The Skill Atrophy Concern

### 8.1 The Deskilling Literature

**Braverman, Harry, *Labor and Monopoly Capital* (Monthly Review Press, 1974)**
The foundational text on deskilling. Management systematically deskills labor by embedding craft knowledge into machines and processes, reducing workers to machine-tenders who execute but don't understand. Applied to AI: if workers delegate cognitive tasks and stop performing them directly, skills atrophy. The AI becomes the repository of the skill; the human becomes the operator who initiates and accepts output without the ability to evaluate it. This is precisely the Self-Automator pattern.

**Carr, Nicholas, *The Glass Cage: How Our Computers Are Changing Us* (W.W. Norton, 2014)**
Documents automation-induced skill erosion across domains: pilots who can't fly manually, architects who lose spatial intuition, navigators who lose wayfinding. The pattern is consistent: when a tool handles a cognitive task, the human skill degrades through disuse. The concern for AI: extensive reliance for writing, analysis, or code means the underlying human skill begins to erode, potentially below the level needed to evaluate AI output. You lose the ability to judge what the tool produces.

**Bainbridge, Lisanne, "Ironies of Automation" (Automatica 19(6), 1983)**
The more reliable an automated system is, the less the human operator practices the skill needed to take over when the system fails — but the more reliable the system, the more consequential the failure when it does occur. Applied to AI: if AI handles 90% of a cognitive task reliably, the human loses the skill for the 10% where AI fails — which is precisely the 10% where human judgment matters most (the edge of the jagged frontier).

**Parasuraman & Manzey, "Complacency and Bias in Human Use of Automation" (Human Factors 52(3), 2010)**
When automation is generally reliable, humans rationally reduce monitoring and verification effort. When the system errs, the error goes undetected. Extended play with AI that mostly works well builds complacency, reducing the user's tendency to verify output. The skill of critical evaluation atrophies alongside the domain skill.

**Sparrow, Liu & Wegner, "Google Effects on Memory" (Science 333(6043), 2011)**
When people know information is available externally, they encode it less deeply in memory. The brain adapts to offloading by reducing internal storage. Suggests a mechanism for how AI reliance could erode deeper cognitive skills: if AI handles analysis, the brain reduces investment in analytical capacity.

### 8.2 The Counter-Argument: Play as Deskilling Prevention

**Beane, Matt, "Learning to Work with Intelligent Machines" (HBR, September-October 2019); and *The Skill Code* (HarperBusiness, 2024)**
Studied surgical residents, police trainees, and investment banking analysts. AI and robotic systems disrupted the traditional "challenge, complexity, connection" pathway of skill acquisition — when AI handles the challenging parts of a task, novices never develop the skills that come from struggling with difficulty. But Beane's concept of **"shadow learning"** — finding unofficial ways to get hands-on practice when official workflows route hard work to machines — directly parallels the argument for deliberate play. The solution to deskilling is not avoiding AI but ensuring that engagement with AI includes deliberate encounters with difficulty.

**The play-based resolution:** The deskilling concern is real and serious, but it applies to *delegation without engagement* (Self-Automator mode), not to *play*. Play, by definition, involves active engagement with the tool. The question is whether play sustains the human skill or erodes it. The answer depends on the play's structure: play that includes evaluation, reflection, and deliberate struggle with difficult tasks sustains skill. Play that accepts output uncritically (vibe coding at the extreme) accelerates deskilling.

---

## 9. Expanding: How Play Connects to the Three-Part Framework

This section maps play onto the three claims developed in Parts 1-3 of the practical narrative, showing that play is not just "the next section" but the resolution of all three problems simultaneously.

### 9.1 Play Breaks the Enchantment (Part 1 — The Talking Library)

**Winnicott, D.W., *Playing and Reality* (Tavistock, 1971)**
Winnicott's "transitional space" is the zone between subjective experience and objective reality where you can test the properties of an object without full consequences. Play creates the transitional space where you encounter AI's failures without the cost of those failures in real work. Seeing the tool fail — generating nonsense, hallucinating, missing the point — moves you from "talking to an intelligence" to "using a tool with specific, observable limitations." Winnicott's insight: this can only happen through active engagement, not through being told.

**Piaget, Jean, *Play, Dreams and Imitation in Childhood* (W.W. Norton, 1962)**
Children develop accurate mental models of objects through play — specifically through encountering the gap between expectation and reality. When a child expects a block to behave one way and it behaves differently, that discrepancy drives learning. The moments in play where AI fails to meet expectations are the moments that build calibration. The enchantment breaks not through argument but through the accumulation of experienced discrepancies.

**Tetlock, Philip, *Expert Political Judgment* (Princeton, 2005); and Tetlock & Gardner, *Superforecasting* (Crown, 2015)**
People become well-calibrated through repeated cycles of prediction, observation, and updating. Calibration is a skill developed through practice, not a trait. Play provides the prediction-observation-update cycle: you predict what AI will produce, observe what it actually produces, update your model of where it works. This is the mechanism by which play builds the calibration that breaks the enchantment.

### 9.2 Play Maps the Frontier (Part 2 — Taxonomy of Multiplication)

**Levi-Strauss, Claude, *The Savage Mind* (University of Chicago Press, 1966)**
The tinkerer (bricoleur) works with whatever is at hand, improvising solutions from available materials, discovering capabilities through use rather than starting from theory. Because the jagged frontier cannot be predicted from theory, bricolage is the epistemically appropriate approach: you discover what AI can do by trying things, not by reading documentation.

**March, James G. (Organization Science, 1991)**
Exploration is the process of discovering new possibilities — what works, what doesn't, where the boundaries are. The jagged frontier is precisely the territory that requires exploration because its contours cannot be deduced from first principles. Play IS exploration applied to the capability frontier.

**The multi-armed bandit problem (Robbins, 1952; Gittins, 1979; extensive subsequent literature)**
The exploration-exploitation tradeoff formalizes when playing (exploring) is more rational than executing (exploiting). When you are uncertain about the payoff distribution — which is exactly the situation with AI's jagged frontier — exploration has high expected value because each experiment reduces uncertainty. The more jagged and unpredictable the frontier, the more valuable play becomes relative to following established practices.

### 9.3 Play Exercises Agency (Part 3 — Agency Upstream)

**Vygotsky, Lev, *Mind in Society* (Harvard University Press, 1978)**
Play is the leading activity through which children develop self-regulation — the capacity to control behavior according to internal rules rather than external stimuli. In play, the child is simultaneously actor and rule-maker. Applied to AI: play positions the user as experimenter-evaluator, not as recipient of AI output. You decide what to try, evaluate the result, adjust your approach. This is the opposite of the Self-Automator mode.

**Bandura, Albert, *Self-Efficacy: The Exercise of Control* (W.H. Freeman, 1997)**
People develop agency through "mastery experiences" — successfully performing challenging tasks. Play provides low-stakes mastery experiences: you set a challenge, work through it with the tool, evaluate the result. Each cycle builds competence and control over the tool. Agency develops through repeated cycles of intention-action-evaluation.

**Sennett, Richard, *The Craftsman* (Yale University Press, 2008)**
Craftwork develops through a dialogue between maker and material — the maker acts, the material responds, the maker adjusts. The play mode of AI engagement replicates this dialogue: you prompt, the tool responds, you evaluate and adjust. Each cycle is an exercise of agency — you are making decisions about what to try, what to accept, what to reject, what to modify. The craftsman is not a passive recipient of the material's properties; they actively explore, test, and shape.

### 9.4 The Unified Argument

Play is the mode that simultaneously:
- **Breaks the enchantment** by forcing encounters with AI failure (Part 1)
- **Maps the frontier** by exploring where AI helps and where it hurts (Part 2)
- **Exercises agency** by positioning the user as experimenter and evaluator, not as passive recipient (Part 3)

No other mode does all three. Instruction can explain the enchantment but cannot break it experientially. Best practices can describe the frontier but cannot map it for your specific use case. Rules can mandate agency but cannot build the capacity for it. Play — structured, reflective, domain-grounded play — is the only mode that addresses all three problems through a single practice.

---

## 10. Expanding: Organizational Resistance to Play

### 10.1 Why Organizations Under-Explore

**March, James G., "Exploration and Exploitation in Organizational Learning" (Organization Science 2(1), 1991)**
Organizations systematically under-explore because exploitation (refining what you already know) produces faster, more certain, more proximate returns than exploration. Managers see exploration as waste because its returns are uncertain, delayed, and accrue broadly rather than to any specific project. This is why "playing with AI" feels like wasting time in professional contexts — it is exploration, and organizations are structurally biased against exploration.

**Edmondson, Amy, "Psychological Safety and Learning Behavior in Work Teams" (ASQ 44(2), 1999); and *The Fearless Organization* (Wiley, 2019)**
Experimentation and exploratory learning happen only in teams with psychological safety — where people can try things, fail, and discuss failure without penalty. If "playing with AI and discovering it doesn't work for this task" is treated as wasted time rather than valuable frontier-mapping, people stop exploring and revert to either avoidance or uncritical adoption.

**Christensen, Clayton, *The Innovator's Dilemma* (HBS Press, 1997)**
Established organizations resist disruptive technologies because they don't fit existing performance metrics. AI play doesn't fit into quarterly reviews or project timelines. The resistance follows directly from how organizations measure value — but it means the learning that matters most (discovering the jagged frontier) happens outside official channels or not at all.

### 10.2 The Cynefin Connection

**Snowden, David (with Mary Boone), "A Leader's Framework for Decision Making" (HBR, November 2007); and the Cynefin framework (1999-present)**
Complex domains require probe-sense-respond — try things, see what happens, adapt. AI's jagged frontier makes it a complex domain: you cannot predict in advance where it will help or hurt. Organizations that demand analyze-plan-execute for AI adoption are applying a complicated-domain strategy to a complex-domain problem. Play IS the probe-sense-respond approach. Organizational resistance to play is resistance to the epistemically appropriate strategy.

### 10.3 Lead Users and Innovation

**Von Hippel, Eric, *Democratizing Innovation* (MIT Press, 2005)**
The most valuable innovations come from users who experiment with tools beyond their intended use — tinkering, repurposing, pushing limits. Organizations that prevent this experimentation lose the innovation benefits. The people who discover AI's real capability frontier are the tinkerers who play with it in unexpected ways, not the people who follow official training materials.

---

## 11. Noted Gaps

### Gap 1: No Longitudinal Studies of Play-Based AI Learning
The BCG study is cross-sectional. The METR study is short-duration. We have no research tracking how play-based AI engagement develops over months or years. Does the Cyborg pattern sustain? Do people who play eventually transition to deliberate practice, or does play plateau?

### Gap 2: The Organizational Play-Learning Bridge
March explains why organizations under-explore, and Edmondson explains what makes exploration safe. But nobody has studied what organizational structures support *play-based AI adoption* specifically. What does an AI playground look like inside a company?

### Gap 3: Play and Equity
The "just use it" discourse assumes access to paid tiers, time to experiment, and a professional context where AI experimentation is rewarded rather than punished. Who gets to play? Who is forced to use AI without the luxury of exploratory learning? The equity dimension of play-based AI literacy is almost entirely unexamined.

### Gap 4: The Deskilling-Play Interaction Over Time
We know delegation without engagement causes skill atrophy (Braverman, Carr, Bainbridge). We know play sustains engagement. But we don't know the long-term interaction: does even engaged play eventually erode skills, just more slowly? Or does play actually *develop* new skills that partially compensate? The temporal dynamics are unknown.

### Gap 5: Non-Professional Play
Almost all the research and practitioner writing focuses on professional use — coding, consulting, writing. What about play with AI that is genuinely recreational? People using AI for entertainment, creative exploration, personal projects. Is this wasted time, or does it build transferable AI literacy?

### Gap 6: Cultural Variation in Play
The entire discourse is overwhelmingly Western and English-speaking. Do different cultural attitudes toward play, experimentation, error, and authority produce different patterns of AI engagement? The non-Western angle is almost completely absent from the literature on learning to use AI.

### Gap 7: Play and the Three-Part Binding
The argument that play simultaneously breaks enchantment, maps the frontier, and exercises agency is (as far as this research can determine) original. Nobody has made this specific connection. It is a genuine contribution space but also means it lacks empirical validation.

---

## 12. Source Index

### Empirical Studies
| Source | Date | Key contribution |
|--------|------|-----------------|
| Dell'Acqua, Mollick et al. (HBS / Organization Science) | 2023/2025 | Cyborg vs. Centaur vs. Self-Automator patterns; jagged frontier |
| METR developer productivity study | 2025 | 19% slower / believed 20% faster paradox |
| Brynjolfsson, Li, Raymond (QJE) | 2025 | 34% novice boost, near-zero expert gain |
| GitClear code quality report | 2024 | AI-assisted code shows higher churn rates |
| Uplevel engineering study | 2024 | 41% bug rate increase with Copilot in some cohorts |
| McKinsey developer productivity | 2023 | 30-50% faster on well-defined tasks |
| Zamfirescu-Pereira et al. (CHI) | 2023 | Non-experts learn through trial and error, not instruction |
| Tankelevitch et al. (CHI) | 2024 | AI use develops metacognitive skills through experience |
| Kazemitabaar et al. (CHI) | 2023 | Scaffolded tinkering beats prohibition and unrestricted use |

### Practitioner Writing
| Source | Key contribution |
|--------|-----------------|
| Mollick, *Co-Intelligence* (2024) | Experimentation as core AI skill; impossibility of learning through instruction |
| Mollick, "One Useful Thing" (2023-present) | Ongoing modeling of Cyborg-pattern engagement |
| Willison, simonwillison.net (2023-2025) | Building to understand; vibe coding distinction; AI literacy as ongoing practice |
| Appleton, maggieappleton.com (2023-2025) | Interface constraints on play; folk interfaces; designing for tinkering |
| Shane, AI Weirdness (ongoing) | Creative misuse as epistemic practice |
| Karpathy, X post (Feb 2025) | Coined "vibe coding"; defined the practice |
| Levels (@levelsio, 2025) | Demonstrated vibe coding for indie product development |

### Play Theory and Learning
| Source | Key contribution |
|--------|-----------------|
| Ericsson, Krampe & Tesch-Romer (1993) | Deliberate practice; play-to-practice sequence |
| Papert, *Mindstorms* (1980) | Constructionism; microworlds; learning through building |
| Csikszentmihalyi, *Flow* (1990) | Productive zone between boredom and anxiety |
| Schon, *The Reflective Practitioner* (1983) | Reflection-in-action; doing and evaluating simultaneously |
| Bjork, "Desirable Difficulties" (2012) | Friction enhances learning |
| Winnicott, *Playing and Reality* (1971) | Transitional space; testing without full consequences |
| Piaget, *Play, Dreams and Imitation* (1962) | Calibration through expectation-reality discrepancy |
| Vygotsky, *Mind in Society* (1978) | Play develops self-regulation and agency |
| Sennett, *The Craftsman* (2008) | Skill through maker-material dialogue |

### Counterargument Sources
| Source | Key contribution |
|--------|-----------------|
| Nickerson (1998) | Confirmation bias during exploration |
| Einhorn & Hogarth (1978) | Poor feedback environments entrench illusions |
| Klein (1998, 2007) | Calibration requires salient, consequential failure |
| Fogg (2003) | Trust momentum from positive interactions |
| Moore & Healy (2008) | Three types of overconfidence |
| Steel (2007) | Productive procrastination; play as avoidance |
| Braverman (1974) | Deskilling through automation |
| Carr (2014) | Automation-induced skill erosion |
| Bainbridge (1983) | Ironies of automation |
| Parasuraman & Manzey (2010) | Automation complacency |
| Beane (2019, 2024) | Shadow learning; skill development disrupted by AI |

### Organizational Dynamics
| Source | Key contribution |
|--------|-----------------|
| March (1991) | Exploration vs. exploitation; organizations under-explore |
| Edmondson (1999, 2019) | Psychological safety enables experimentation |
| Christensen (1997) | Disruptive technologies resist existing metrics |
| Snowden (2007) | Cynefin; probe-sense-respond for complex domains |
| Von Hippel (2005) | Lead users innovate through experimentation |
| Amabile (1983, 2016) | Domain grounding required for productive exploration |
| Vallerand (1992, 2003) | Harmonious vs. obsessive passion |

### Critical Perspectives on AI Literacy
| Source | Key contribution |
|--------|-----------------|
| Narayanan & Kapoor, *AI Snake Oil* (2024) | Prompt engineering expertise is non-reproducible |
| Bender (various, 2023-2025) | "Just use it" can build false confidence |
| Gebru and AI ethics community | Individual literacy obscures structural questions |
| McQuillan, *Resisting AI* (2022) | Individual frameworks inadequate for societal impacts |
| Eslami et al. (CHI 2016) | Extensive use can produce confident but wrong mental models |

### Prompt Engineering Research
| Source | Key contribution |
|--------|-----------------|
| Wei et al. (NeurIPS 2022) | Chain-of-thought prompting |
| Brown et al. (NeurIPS 2020) | Few-shot learning |
| Weng (2023) | Rigorous survey grounding practice in research |
| Saravia / DAIR.AI (ongoing) | Separating validated techniques from folklore |

### Creative Misuse
| Source | Key contribution |
|--------|-----------------|
| Dourish (2003+) | Technology appropriation as meaning-making |
| Hertz & Parikka (2012) | Understanding technology through intentional misuse |
| Shane (2019+) | Errors more informative than successes |
| Herndon & Dryhurst (2019-2024) | Artists as essential AI R&D |
