# Nature reader, paper miner, and scientific brainstorming

Use for three distinct outputs: a traceable full-paper reader, a deep-reading paper card, or an evidence-based research direction.

## Full-paper reader

Detect the source: selectable PDF, scanned PDF, publisher/preprint HTML, DOI/arXiv link, or pasted text. State the source type, resolve DOI/arXiv first, and preserve the version read. Unless a summary is explicitly requested, produce a full traceable Markdown reader: Chinese-English alignment when translation is requested, figures/tables and legends near the relevant prose, rendered equations, stable source anchors, and a terminology ledger. Preserve an image crop when OCR/transcription is unreliable.

Use explicit grounding states: **page-grounded** (reliable PDF pages plus structure), **structure-grounded** (reliable sections/figures/tables/equations but no page numbers), or **source-limited** (abstract, metadata, or excerpt only). Never fabricate page numbers or silently downgrade a full reader to a summary; record missing or low-confidence material in notes.

## Paper miner / card

For one paper, establish the source boundary, then classify it by evidence structure: methods, discovery, resource, clinical, materials, or review. Inventory metadata, question, contribution, method/data flow, every main figure/table/equation and its argumentative role, experiments/baselines/metrics/results, limitations, and stable source pointers. Build a claim-evidence matrix before interpretation. Separate author facts, agent analysis, external field history, and proposed ideas. Mark unsupported sections `Not assessable from supplied material`.

## Scientific brainstorming

Turn reading into a gap analysis: known evidence, methods used, conflicts, missing measurements/mechanisms/comparisons, and the feasible test that would close the gap. Treat novelty as a hypothesis until verified. Each idea needs a mechanism, expected observation, falsifier, resource burden, and first experiment. Compare importance, tractability, evidence burden, differentiation, and fit.
