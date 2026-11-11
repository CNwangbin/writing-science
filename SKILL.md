---
name: writing-science
description: Revise, polish, restructure, condense, or critique scientific writing — journal papers and their sections (abstract, introduction, methods, results, discussion, conclusion), grant proposals (NSF, NIH, ERC, 国自然/NSFC 申请书, 立项依据, 科学问题), theses, and plain-language summaries — by applying Joshua Schimel's "Writing Science" (OCAR story structure, knowledge gaps, topic and stress positions, flow, strong verbs, jargon control, condensing, top-down SCFL editing). Use whenever the user asks to 修改、润色、改写、精简、压缩字数、审阅、提意见、中译英并润色, or to polish, edit, tighten, rewrite, or review any scientific or academic text, in Chinese or English, even if they just paste a paragraph and say "帮我改一下" or "make this read better". Also use for questions about framing a research question or hypothesis, opening or ending a paper, writing about limitations, or explaining research to non-specialists.
---

# Writing Science: revising papers and proposals

A scientific paper is a story about how nature works, built from data but not the same as the data. Readers cite and fund work they can follow, so the governing principle is: **it is the author's job to make the reader's job easy.** Every guideline below serves that principle. When a guideline (short subjects, active voice, cut every spare word) works against it in a particular sentence, break the guideline and keep the principle.

Revise top-down. A polished sentence inside a paragraph that should be deleted is wasted work, and many sentence-level symptoms (a weak verb, a clumsy transition) have structural causes (an unstated question, two ideas fighting for one paragraph). Fix the story first, then the words.

## Reference files

- `references/principles.md`: the principles with diagnostic tests and fix patterns, in 18 numbered sections with a table of contents. Read the sections that match the problems you see.
- `references/section-guide.md`: checklists for abstracts, introductions, methods, results, discussions, proposals, and NSFC applications. Read the part for the section you were given before diagnosing it.

For a one- or two-sentence fix, the "common high-value fixes" list at the end of this file is usually enough. For a paragraph or more, read the relevant reference sections first: the fix patterns there are more specific than this overview.

## Step 1: Establish the context

Work out three things before touching the text. Infer them when you can and state your assumption in one line. Ask only when the text is long and the answer would change the whole revision.

**What is it?** Document type and section. A Results paragraph and a Discussion paragraph need different things, and a proposal is read differently from a paper.

**Who reads it, and how patient are they?** The audience's patience decides the story structure and how much each term needs defining.

| Audience | Patience | Structure | Opening move |
|---|---|---|---|
| Specialist journal | Patient; wants to watch the evidence unfold | OCAR (question at end of intro, conclusion at end) | A positioning "pawn push" is fine |
| Generalist journal (Nature, Science, PNAS) | Low; editor triages in minutes | LDR (lead carries problem + finding) | Launch a queen: a strong, concrete claim |
| Grant panel | Lowest; decides in the first 1–2 pages | ABDCE or LDR, plus an explicit resolution | The exciting question up front |
| Public / policy | Impatient, no shared schemas | LDR, message box | "Who knew?" or "what it means for you" |

**What kind of help was asked for?** Match the depth of the edit to the request. Authors who ask for a light polish and get a rewrite have to re-verify every sentence.

| Request | What to do |
|---|---|
| 只改语法 / proofread / fix grammar only | Correct errors and nothing else. Mention at most one or two larger issues in a closing note. |
| 润色 / polish / language edit | Sentence- and word-level work (Clarity, Flow, Language). If there is a structural problem, report it in a line or two and offer to fix it; don't silently restructure. |
| 修改 / 改写 / revise / "why is this weak" | Full top-down pass, structure included. |
| 精简 / 压缩到 N 字 / cut to N words | Condense in the order given in principles §16 (cut blocks, repair arcs, then words). Report word counts before and after. If the target can't be reached without losing content, say what would have to go and let the author choose. |
| 审阅 / 提意见 / review / feedback | Diagnose only: prioritized problems, each with one short example of the fix. Don't rewrite the whole text unless asked. |
| 中译英 / translate and polish | Don't translate sentence by sentence. Work out the story (O, C, A, R) of the Chinese text, then write English that follows English topic–stress order. Chinese drafts often put background and qualifiers first and the point last in long sentences; split them and bring the subject and verb forward. |

## Step 2: Diagnose top-down with SCFL

Go through the four levels in order. Note problems at each level before rewriting, because the fixes interact.

1. **Structure.** Can you name the opening problem, the specific question (challenge), the action, and the resolution? Is the question stated as a question ("to learn X, we did Y"), or only as data-collection objectives? Does the resolution answer the question and return to the problem the opening raised, at the same width? Does each section, subsection, and paragraph form one complete arc, or does an idea appear, vanish, and come back?
2. **Clarity.** Is each claim concrete (numbers, named mechanisms, specific gaps) rather than fuzzy ("little is known", "plays an important role", "affects")? Are actions carried by verbs, or buried in nominalizations and fuzzy verbs? Does this audience hold the schema behind each technical term?
3. **Flow.** Does each sentence's topic pick up something already introduced (often the previous sentence's stress)? Does each paragraph's opening connect to the previous paragraph's resolution? Do all sentences in a paragraph serve one theme?
4. **Language.** Filler, redundancy, obvious statements, empty amplifiers, metadiscourse, long Latinate words where short ones work, prepositional chains, noun trains. Would it survive being read aloud?

Then loop: tightening the language often exposes a new structural option (for example, the first sentence turns out to be a throat-clearing pawn push that can go).

**If the text is already good, say so.** Point out what works, make the few changes that help, and stop. Rewriting sound prose to show effort only gives the author more to check.

## Step 3: Revise

- **Preserve the science.** Keep the data, citations, and the strength of claim the evidence supports. Do not invent numbers, mechanisms, or conclusions. When the right fix needs information only the author has (the fold-change behind "dramatically", the real question behind a list of objectives), write the revision with a bracketed placeholder such as `[×?-fold]` or `[state the question: does X control Y?]`, and list it under questions for the author.
- **Keep honest hedges; cut empty ones.** "May" or "suggests" that reflects real uncertainty stays: removing it makes a claim the data don't support. What goes is stacked or reflexive hedging ("may possibly suggest that it could") and caveats in the final power position.
- **Break rules for the principle.** Use the passive when it puts the right character in the topic position or when the actor doesn't matter. Lengthen a subject if that links the sentence to the one before it. Keep the few "extra" words that carry flow. Keep a nominalization that names a concept the reader already holds ("gene expression") or sums up an argument ("these limitations").
- **Keep terms consistent.** In science, a new word signals a new thing. If the author says "biomass" in one sentence, don't vary it to "abundance" for elegance.
- **Don't add what you are cutting.** A revision that introduces its own amplifiers and stock phrases ("crucial", "pivotal", "sheds light on", "a comprehensive understanding") has traded one kind of filler for another.
- **Respect the field and the author.** Some fields expect formal hypotheses and some expect questions; some combine Results and Discussion. Keep the author's voice unless it is causing the problem.
- **Chinese text.** The same principles apply. Typical equivalents: "对……进行了研究/分析" is a nominalization with a fuzzy verb (use "研究了/分析了" or a concrete verb); "目前国内外对……研究较少" is the "little is known" problem (state what exactly is unknown); "具有重要意义" / "起着重要作用" are fuzzy (say what it does); long chains of "的" are the Chinese noun train. End-of-sentence emphasis holds in Chinese too, so put the new, important information last.

**Working in files.** When the text is in a file (.tex, .md, .docx, .txt) rather than pasted:
- Leave markup intact: LaTeX commands, `\cite{}` and `\ref{}` keys, labels, equations, figure and table environments, Markdown syntax. Edit the prose around them.
- Don't overwrite the author's file unless they ask for in-place edits. Write the revision to a new file next to it (for example `intro_revised.tex`) or show the revised passages in the reply, so they can compare.
- For .docx, use the docx skill if it is available, with tracked changes when the author wants to review edits one by one.

**Before returning the revision, check it against the original:** every number, citation, and claim is still there (or its removal is listed); no claim got stronger than the evidence; the last sentence of each paragraph ends on its point; you added no facts.

## Step 4: Present the result

Write explanations in the user's language, with headings in that language only. Keep the revised text in the document's language unless asked to translate. Use these four parts, scaled to the job:

1. **Diagnosis (诊断).** One or two sentences on the biggest problem, then a short list by level, structural issues first.
2. **Revised text (修改稿).** The full revised passage, ready to paste.
3. **What changed and why (修改说明).** Original → revised → principle. Group repeated fixes instead of listing every instance. Naming the principle lets the author apply it next time.
4. **Questions for the author (需要作者确认).** Placeholders you inserted and decisions only the author can make. Omit this part if there are none.

A small job gets a small answer. For example, asked to polish "It was observed that there was a significant increase in root biomass in the drought treatment (p < 0.05).":

```
**Diagnosis:** the topic is buried behind "It was observed that", the action sits in
a noun ("increase"), and the sentence reports significance without the size of the effect.

**Revised:** Drought increased root biomass by [×?-fold or %] (p = [exact value]).

**Needed from you:** the size of the increase and the exact p-value.
```

For a long document (a whole paper or proposal), don't rewrite everything in one pass. First give a structural report: the OCAR map of the document as it stands, where the story breaks, and what to move, cut, or add. Then revise section by section, starting with the Introduction and the concluding paragraph, since those carry the story.

## The most common high-value fixes

Check for these first; together they cover most weak drafts. Section numbers refer to `references/principles.md`.

1. **"Little is known about X."** (§6) Usually false, and contradicted by the paragraph of known facts that follows. Replace it with the specific thing we don't know, bounded by what we do.
2. **Objectives without a question.** (§7) "We measured A, B, and C" leaves the reader guessing why. Rewrite as "To learn X, we did Y". Put the most important goal first, not the methods-validation goal.
3. **Literature review instead of introduction.** (§6) "Smith (2003) found X. Jones (2005) found Y." makes researchers the characters. Make nature the subject: "X occurs (Smith 2003)". Name researchers only to frame a debate. Use known facts only to outline the gap.
4. **Solution before problem.** (§6) A method or model introduced before the reader knows what problem it solves. Sell the problem first.
5. **Openings with no direction, or misdirection.** (§5) Textbook background that fits a hundred papers, or a first paragraph that points one way while the paper goes another. Open with the problem this paper addresses and introduce its main characters.
6. **Endings that undermine.** (§9, §17) "More research is needed", "If X can be fully established…", or limitations as the last word. Use "but, yes": state the limitation first, then end with what was learned and how it answers the opening problem.
7. **New ideas in the conclusion.** (§9) If a new implication appears only at the end, weave it into the introduction or move it out.
8. **Statistics instead of data.** (§8) "Significantly increased (p < 0.05)" hides the story. Give the size of the effect with the p-value: "2.3× higher (p = 0.02)". Don't report a 2.3× difference at p = 0.07 as "no effect".
9. **Results without a lead.** (§8) State the pattern first, then the details.
10. **Sentence structure.** (§12) A long subject before the verb; a buried topic ("It has been predicted that…"); words trailing after the real stress; new terms in the topic position.
11. **Dead verbs.** (§14) Nominalizations ("conducted an investigation of") and fuzzy verbs (affect, facilitate, mediate, occur, perform). Find the action and put it in the verb.
12. **Fuzzy hypotheses.** (§14) "X is controlled by A, B, and C" is a truism. Make it falsifiable: "A is the strongest control on X".
13. **Filler.** (§16) "In this study, we found that", "It is worth noting that", "There is evidence that", "very / highly / dramatically", "structural and functional changes". Cut words that add no content, clarity, or flow.
14. **Broken links.** (§13) A sentence whose topic connects to nothing before it. Check whether it belongs in this paragraph at all before forcing a transition.
