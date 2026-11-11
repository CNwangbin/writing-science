# writing-science

A [Claude Code](https://claude.com/claude-code) skill for revising scientific papers and grant proposals, in Chinese or English. It applies the principles of Joshua Schimel's *Writing Science: How to Write Papers That Get Cited and Proposals That Get Funded* (Oxford University Press, 2012).

一个用于修改、润色科研论文和基金申请书（含国自然）的 Claude Code skill，依据 Joshua Schimel 的《Writing Science》。

## What it does

When you ask Claude Code to polish, revise, condense, or review a scientific text (修改、润色、精简、审阅), the skill:

1. Works out the document type, the audience, and how deep an edit was requested (grammar only, polish, full revision, condense to N words, review only, or translate and polish).
2. Diagnoses top-down in SCFL order: Structure → Clarity → Flow → Language.
3. Revises without inventing data, using placeholders like `[×?-fold]` for information only the author has.
4. Returns a diagnosis, the revised text, what changed and which principle each change follows, and questions for the author.

## Install

Clone into your personal skills folder:

```bash
git clone <this-repo-url> ~/.claude/skills/writing-science
```

Claude Code loads it automatically; check with `/skills`.

## Layout

| Path | Contents |
|---|---|
| `SKILL.md` | Workflow and a quick list of the most common fixes |
| `references/principles.md` | The book's principles as diagnostic tests and fix patterns |
| `references/section-guide.md` | Checklists for each section of a paper, grant proposals, and NSFC applications |
| `evals/` | Test cases in the `claude plugin eval` format |

The reference files paraphrase the book's principles; the examples are newly written. The abstract checklist, the NSFC section mapping, and the Chinese-language notes are extensions of the book's framework, not part of the book.
