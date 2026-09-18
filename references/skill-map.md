# ResearchBox unified skill map

This file consolidates capabilities supplied by the installed skills and the
public Nature Skills collection. Use it for routing, not as a checklist to
execute in full.

## Stage map

| User need | Route | Load |
|---|---|---|
| Find a research question or direction | Frame → Research | `strategy.md`, then `research.md` |
| Generate or select ideas | Frame | `strategy.md`; choose one ideation method |
| Search arXiv or related literature | Research | `research.md`; use versioned arXiv records and citation APIs |
| Read/translate/deconstruct a full paper | Research | `nature-reading.md` |
| Mine a paper into a claim/evidence card | Research | `nature-reading.md` |
| Draft or restructure a manuscript | Write | `writing.md`, then `nature-writing.md` when Nature style matters |
| Polish/translate existing academic prose | Write | `writing.md`, `nature-writing.md` |
| Humanize or remove defensive writing | Write | `writing.md`; preserve necessary limitations |
| Simulate peer review | Write → Verify | `nature-figure-review.md` or source material plus reviewer contract |
| Reply to reviewers/editor | Write → Verify | `nature-response.md` |
| Analyze data, statistics, or Jupyter work | Analyze | `analysis.md` |
| Create a scientific figure | Analyze → Design | `analysis.md`, `nature-figure-review.md` |
| Explore UI/design directions | Design | `design.md`; make 2–3 meaningful HTML variants only when direction is open |
| Build a polished HTML artifact | Design | `design.md`; use the actual project stack when it exists |
| Prepare PowerPoint or academic slides | Present | `slides.md` |

## Consolidated source names

These names are aliases for the routes above, not separate mandatory loads:

- **Reading/research:** `arxiv`, `Nature-reader`, `Paper miner`,
  `nature-academic-search`, `Scientific brainstorming`.
- **Writing:** `Nature-writing`, `Nature-polishing`,
  `research-paper-writing`, `humanizer`, `anti-defensive-writing`.
- **Review/revision:** `Nature-reviewer`, `Nature-response`.
- **Analysis/figures:** `jupyter-live-kernel`, `Nature-figure`.
- **Design:** `claude-design`, `sketch`, `popular-web-designs`.
- **Planning/presentation:** `writing-plans`, `powerpoint`.
- **Idea generation:** `ideation`.

## Routing details

### `arxiv` / literature

Use arXiv for discovery and versioned preprints. Search by title, abstract,
author, category, or exact phrase; preserve the version actually read. Check
withdrawal notices. Use publisher/DOI records to establish publication status,
and citation graphs only as discovery/impact signals—not proof of correctness.

### `ideation` / scientific brainstorming

Extract phase (generate, expand, select, unblock, refine, synthesize), domain,
and constraint level. Pick one method that matches the bottleneck. Reject
obvious first answers; every retained idea states mechanism, why now, failure
mode, and smallest falsifying test. For research, verify novelty against
literature rather than treating novelty as a style claim.

### `nature-reader` / Paper miner

Identify source type and version first. For full reading, preserve figure/table/
equation placement and stable anchors; label grounding as page-grounded,
structure-grounded, or source-limited. For a paper card, map claims to evidence,
methods, data flow, experiments, limitations, and research consequences. Never
invent pages, results, citations, or missing sections.

### `nature-writing` / `nature-polishing`

Build problem → gap → contribution → method → evidence → boundary before
sentence polish. Preserve facts, equations, numbers, citations, terminology,
and author voice. Use British spelling only when requested or required. Remove
defensive padding and AI-like filler, but retain uncertainty affecting validity,
ethics, safety, or reproducibility.

### `nature-reviewer` / `nature-response`

Keep reviewer assessment separate from author rebuttal. Review only supplied
material and identify significance, originality, validity, readability,
technical blockers, and recommendation posture. For responses, map every
comment to action, evidence/change, exact location, and status; use
`AUTHOR_INPUT_NEEDED` instead of inventing experiments or line numbers.

### `jupyter-live-kernel` / `Nature-figure`

Use a live kernel for stateful exploration; use a script for repeatable final
generation. Record inputs, versions, seeds, transformations, and sample units.
For figures, define the claim and evidence contract first; check scales, units,
uncertainty, contrast, source-data traceability, editability, and target-size
rendering. AI-generated schematics are conceptual drafts, never experimental
evidence.

### `claude-design` / `sketch` / `popular-web-designs`

Inspect existing tokens, assets, content, and primary action. If direction is
uncertain, create 2–3 disposable variants with different layout/density/
hierarchy stances, realistic content, and at least one visible interaction.
Use design references as principles, not as permission to copy proprietary
screens. Test keyboard/focus, responsive behavior, reduced motion, and the main
state transition.

### `writing-plans` / `powerpoint`

Plans name goal, non-goals, deliverables, dependencies, files/data, success
criteria, and validation; sequence by irreversible decisions and evidence risk.
Slides use one message per slide, question → evidence → interpretation → next
step, and rendered visual QA. Never leave fabricated metrics, citations, or
template placeholders.

## Provenance

The Nature-specific routing is adapted from the public
[Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) project.
The arXiv and ideation behavior follows the local installed skills; design and
presentation behavior follows their local playbooks. This map summarizes
capabilities and does not redistribute upstream assets or code.
