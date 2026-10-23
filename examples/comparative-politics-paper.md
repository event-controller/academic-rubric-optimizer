# Real-World Execution: Political Science Comparative Paper

This example demonstrates a live execution of the **Academic Rubric Optimizer (ARO v3.2)**

- **Model:** Claude Sonnet 5.5
- **Reasoning Configuration:** Effort: High
- **Input Parameters:** 2,500 words, Comparative Politics, 2 cases, 6 peer-reviewed sources, prior instructor feedback

---

## 1. Input: Raw Assignment & Past Feedback

```
COURSE: Political Science 204: Comparative Governance
ASSIGNMENT TYPE: Term Research Paper
LENGTH: 2,500 words
PROMPT: 
"Critically evaluate whether the rise of digital surveillance technology strengthens authoritarian stability or inadvertently creates new vectors for democratic resistance. You must take a definitive, arguable stance. Support your argument with at least six scholarly, peer-reviewed sources and empirical case studies from at least two distinct countries. Address prominent counter-arguments and evaluate the structural stakes of your thesis."

PAST INSTRUCTOR FEEDBACK (from Essay 1):
"Your thesis was far too broad and vague. You spent too much space summarizing general history rather than engaging in critical analysis. I need to see stronger counter-arguments and active student voice in your next submission."
```

---

## 2. Output: Live ARO Execution Plan

# ARO v3.2: Execution Plan

**CONTEXT WINDOW NOTICE:** System loaded and stable. If my responses get inconsistent later, start a new conversation.

---

## FEEDBACK INTEGRATION: Lessons from Last Time

| Instructor flagged | Weighted response in this plan |
|---|---|
| "Thesis far too broad and vague" | Focus pillar +5%, plus a mandatory scope-calibration step |
| "Too much summarizing general history" | Critical Analysis raised to the top weight, with a hard cap on background (see word budget) |
| "Need stronger counter-arguments" | Gap 1 made mandatory, with a dedicated rebuttal section |
| "Active student voice" | Gap 2 weight increased, with a 30% self-rewrite requirement |

**Last time**, your instructor flagged a broad thesis and summary-heavy writing. To improve, make your thesis name a *mechanism*, a *condition*, and *two cases*, and open every paragraph with a claim, not a fact.
**Praised strengths:** none noted in the feedback, so there is no strength to preserve this round.

---

## ASSIGNMENT PARSING

- **Type:** "Term Research Paper" is not one of the nine variants. *Assignment type unclear. Using Standard Essay protocol (argumentative). Specify if different.*
- **Subject:** Digital surveillance, authoritarian stability, and democratic resistance
- **Word count:** 2,500
- **Discipline:** Political Science (Comparative Politics). This assignment shows regime-type, institutional-durability, and cross-case comparison signals. Your instructor likely expects an explicit comparative logic (why these two cases?) and theory-driven argument, not narrative. Mirror that.
- **Interdisciplinary signals:** None strong enough to require a lens decision (technology-studies themes are present but secondary). Proceeding normally.
- **Audience:** Professor, 200-level, with "critically evaluate" and "structural stakes" signaling a high analytical standard
- **Oral/Presentation:** Not detected
- **Group/Collaborative:** Not detected

**SYLLABUS KEYWORD EXTRACTION:** No syllabus content provided. Using generic academic vocabulary. Paste your syllabus or reading list and I'll build your Conceptual Vocabulary List.

**ACTIVE VARIANT:** Standard Essay

---

## WEIGHTING MATRIX

| Pillar | Raw | Normalized | Rationale |
|---|---|---|---|
| 1. Focus & Thesis | 30 | **23%** | "Definitive, arguable stance" (25) + feedback bump (+5) |
| 2. Evidence & Grounding | 25 | **19%** | "Six peer-reviewed sources" + two-country requirement |
| 3. Structure & Logic | 20 | **16%** | No signal; default |
| 4. Mechanics & Conventions | 20 | **15%** | No signal; default |
| 5. Critical Analysis | 35 | **27%** | "Critically evaluate" + "structural stakes" + feedback on summary |

*Weights normalized to sum to 100% (raw total 130; rounded using largest-remainder).*

---

## FUTURE PICTURE

A 2,500-word paper that opens with a one-sentence thesis taking a **conditional, mechanism-based position** and then proves it by comparing two countries. Each body paragraph leads with a claim, delivers evidence from a peer-reviewed source, and ends with your own "so what." A full section confronts the strongest counter-argument and rebuts it. One anomalous case complicates your thesis and is absorbed. The conclusion answers *why this matters for how we understand regime durability and civic resistance*. Background history is limited to a few sentences, only where it is needed to interpret a case.

**Hidden criteria built in:**
- **Gap 1, Alternative Perspectives:** a dedicated counter-argument and rebuttal section
- **Gap 2, Student Voice:** active verbs, varied sentence length, your own phrasing
- **Gap 3, DoK:** Level 3-4 reasoning carries the paper (see Reserved Tasks)
- **Layer 1, Stakes:** a "why now, why here" link to comparative governance debates
- **Layer 2, Reflexivity: ACTIVATED** (Political Science is a social science). Add one sentence in your introduction or conclusion acknowledging the limits of your own perspective, for example, that you are reading these cases through Western-language, Western-published scholarship.
- **Layer 3, Anomalous Evidence:** use this structure: *"While [majority evidence] points to X, [Anomaly Y] presents a challenge. However, Y's limitations (A, B, C) ultimately reinforce the broader pattern because…"*

### Thesis Scope Calibration

**Scope test:** Can "digital surveillance strengthens or weakens authoritarianism" be supported in 2,500 words with six sources and two cases? **No.** It is too broad, which is exactly what your instructor flagged. Pick one narrowing axis:

- **Option A, by mechanism:** Isolate one function (censorship/filtering, biometric or predictive policing, or social scoring) rather than "surveillance" as a whole.
- **Option B, by regime type:** Argue the effect is *conditional* on regime capacity (for example, closed vs. competitive authoritarian systems). This suits a comparative course well.
- **Option C, by event window:** Anchor on one protest cycle or crackdown period in each country.
- **Option D, by theoretical lens:** Use the "dictator's dilemma" or repression-versus-co-optation framing as your analytical engine.

**Thesis formula (fill the brackets yourself):**
*"Digital surveillance [strengthens / undermines] regime stability under [condition] because [mechanism], as shown in [Country A] and [Country B], though [stated limit]."*

**Thesis Quality Test:** Arguable? Specific? Defensible? Complex? All four must be yes. Submit your draft thesis and I'll run the test.

---

## BACKWARDS-MAPPED STEPS

Write in this order, **conclusion first, introduction last**. Word budget totals 2,500: intro ~13%, body ~76%, conclusion ~11%.

| # | Step | DoK | Target words |
|---|---|---|---|
| 1 | **Conclusion + Stakes:** answer "So what?" for comparative governance; add reflexivity sentence | **4** | ~270 |
| 2 | **Rebuttal** of the strongest counter-argument | **3** | ~250 |
| 3 | **Counter-argument** presented fairly and at full strength | 2 | ~150 |
| 4 | **Anomalous evidence:** one case that complicates your thesis, then absorb it | **3** | ~300 |
| 5 | **Case 2 evidence + analysis** (claim → evidence → "why it matters") | 2→3 | ~600 |
| 6 | **Case 1 evidence + analysis** | 2→3 | ~600 |
| 7 | **Introduction:** hook, a *minimal* context (2-3 sentences max), thesis, roadmap | 3 | ~330 |

**Anti-summary rule:** Cap historical background at roughly 100 words total. If a sentence describes what happened and doesn't argue anything, cut it or tie it to your claim.

---

## OUTLINE AUDIT

Before drafting, submit your planned structure for review. Checklist:

- [ ] All sections present (intro, two cases, counter-argument, anomaly, conclusion)
- [ ] Counter-argument placed with a rebuttal
- [ ] Anomalous evidence included
- [ ] Stakes articulated
- [ ] Reflexivity sentence planned
- [ ] Each paragraph has one clear job
- [ ] Word distribution within 10-15% / 70-80% / 10-15%

*Outline audit available. Submit your planned structure for review.*

---

## DATA COMPILATION PROMPTS (Ready to Copy)

**Prompt 1: Case Selection (DoK 1-2).** "I'm writing a 2,500-word comparative paper on digital surveillance and regime stability. Give me 5 candidate countries with a one-line reason each why they'd make a strong contrasting pair (consider China, Russia, Iran, Hong Kong, Belarus, Egypt/Tunisia), and what variable differs between each pair."

**Prompt 2: Source Hierarchy (DoK 1).** "For the topic of digital repression and authoritarian durability, give me 2-3 example sources for each tier: peer-reviewed articles, government/institutional reports, academic-press books, grey literature, and popular press. Mark which ones count as peer-reviewed."

**Prompt 3: Strongest Counter-Argument (DoK 2, rebuttal is yours).** "My thesis is [your thesis]. State the strongest scholarly counter-argument and the empirical evidence supporting it." *Then write the rebuttal yourself.* Since your stance isn't chosen yet, the likely counters are:
- If you argue **stability strengthened**, the counter is that surveillance creates resistance vectors (leaks, circumvention tools, mobilization via platforms, e.g., Iran 2022, Hong Kong 2019).
- If you argue **resistance vectors**, the counter is surveillance durability (e.g., China's capacity for preemptive repression and targeted co-optation).

**Prompt 4: Anomaly Search (DoK 2).** "Given my thesis [thesis], identify 2 cases or findings from the comparative-politics literature that cut against it, and explain what each shows."

**Prompt 5: Discipline Evidence (DoK 2).** "Summarize how comparative politics scholars distinguish repression from co-optation, the dictator's dilemma, and regime durability, with the key debates for each."

**Prompt 6: Gap Analysis (DoK 3-4, reserved for you).** *Answer this yourself:* "What has NOT been argued in the literature on surveillance and regime stability? What remains unanswered? Where does my thesis fill that gap?"

### Starting Leads (verify every detail in your library before citing)
These are real scholarly directions, but confirm citations, years, and peer-review status yourself:
- King, Pan & Roberts on Chinese censorship (*American Political Science Review*, 2013): Tier 1
- Xu Xu on surveillance, repression, and co-optation (*American Journal of Political Science*, 2021): Tier 1
- Guriev & Treisman, "Informational Autocrats" (*Journal of Economic Perspectives*, 2019): Tier 1
- Feldstein, *The Rise of Digital Repression* (Oxford UP, 2021): Tier 3
- Tufekci, *Twitter and Tear Gas* (Yale UP, 2017): Tier 3

### Source Accessibility
Your prompt requires **six peer-reviewed sources**, so Tier 2 substitution does **not** satisfy the requirement. If you hit a paywall, try these in order: Google Scholar's "All versions" link, your university library portal, SSRN or other preprint servers, author emails or ResearchGate, then interlibrary loan (2-5 days). Start early because of that lead time.

---

## HIGH-DOK RESERVED TASKS (Your Brain Only)

You write these yourself:
1. Your thesis and its stated limit
2. The rebuttal to the counter-argument
3. The absorption of the anomaly ("why Y's limitations reinforce the pattern")
4. The "So What?" and structural stakes in your conclusion
5. The reflexivity sentence
6. Cross-case comparison logic (why these two cases, and what the contrast proves)
7. Gap identification (Prompt 6)

**You cannot outsource these. If you do, your grade caps at B.**

**Voice requirement (Gap 2):** Rewrite at least 30% of anything compiled in your own words. Use active verbs, vary sentence length, and drop formulaic openers like "It is important to note." Your instructor flagged voice specifically.

---

## REVISION LOOP PROTOCOL

After your first draft, submit it and I'll return:
1. A comparison against this Future Picture (missing, underdeveloped, or structural problems)
2. A prioritized revision checklist with time estimates
3. A paragraph-level audit (topic sentence, evidence, analysis, transition)
4. A word-count distribution check (flag if intro >20% or conclusion <5%)
5. A citation audit: every in-text citation matched to a reference entry and vice versa, in your required style
6. **Read-aloud voice check:** read the draft aloud; any sentence that sounds unnatural gets rewritten

---

## GRADE TARGET

No grade target specified. Defaulting to A/A+ protocol. If targeting lower, ignore advanced features.

---

## ESCALATION PATH

If blocked at any point, reply **[STUCK]** and describe where. You have sources but no argument? I'll run the bottom-up thesis protocol (source inventory → pattern detection → thesis translation → thesis test). You are not required to complete all tasks at once. Work through one at a time.

---

## NEXT ACTION

**Choose a narrowing axis (A-D), pick your two countries, and send me a one-sentence draft thesis using the formula above.** I'll run the thesis quality test before you build anything else.

Two quick clarifiers, if you have them: which **citation style** your course requires (APA, Chicago, etc.), and whether you want a **grade target** other than A/A+. And if your deadline is tight, say "QUICK MODE" and I'll condense this to the matrix, future picture, and three actions.
