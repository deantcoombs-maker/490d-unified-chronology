# 490d Repository Style Guide v2.5

Style Guide Version: v2.5
Revision date: June 10 2026
Prior version: v2.4 (June 9 2026 state, retained unaltered as the prior-version file)
Canonical source: Markdown
Status: Revised control file; v2.5 consolidated-workflow and control-architecture update under Repository Revision Plan v3.0; §2A and §27 rewritten from six sequential passes to the Unified Revision Pass with five editorial layers and a diff-based Verification Pass; §30 prompt template updated; per-file vocabulary (§31.38–§31.167, §32A–§32U, and File_36 / File_41 / File_45 glossary additions) migrated verbatim to State_Vocabulary_Register v1.0 with numbering preserved; historical Update Records and the v2.4 Revision Log Addendum migrated verbatim to Repository_Change_Archive v1.0; all editorial rules, terminology standards, number formatting, sign conventions, modal-state rules, Machine Guard formats, claim-status labels, Mirror protocols, and arithmetic controls retained unchanged; diff-audited June 10 2026; companion-control pointers refreshed to Register v1.3 / Procedures v3.1 / Capsule v11.4 / Archive v1.4 (June 10 2026, author-directed); companion-control pointers refreshed to Register v1.6 / Procedures v3.2 / Capsule v11.7 at File_40 integration (June 11 2026, author-directed one-line pointer update; the prior Active-companion line read Archive v1.3 against the June 10 status note of v1.4 — corrected to the last-attested v1.4, with the Archive's current location unconfirmed and under author review); companion-control pointers refreshed to Register v1.10 / Procedures v3.2 / Capsule v11.9 after File_50c integration (June 18 2026, author-directed one-line pointer update; no Style Guide rules, terminology standards, Machine Guards, claim-status labels, arithmetic controls, or repository procedures changed); companion-control pointers refreshed to Register v1.11 / Procedures v3.2 / Capsule v11.10 after File_55 integration (June 20 2026, author-directed one-line pointer update; no Style Guide rules, terminology standards, Machine Guards, claim-status labels, arithmetic controls, or repository procedures changed); companion-control pointers refreshed to Register v1.12 / Procedures v3.2 / Capsule v11.11 after the File_34 / File_55 hybrid Alulim clarification (June 21 2026, author-directed one-line pointer update; no Style Guide rules, terminology standards, Machine Guards, claim-status labels, arithmetic controls, or repository procedures changed); companion-control pointers refreshed to Register v1.13 / Procedures v3.2 / Capsule v11.12 after the File_52a / File_52b post-final cross-file audit (June 26 2026, author-directed one-line pointer update; no Style Guide rules, terminology standards, Machine Guards, claim-status labels, arithmetic controls, or repository procedures changed); companion-control pointers refreshed to Register v1.14 / Procedures v3.2 / Capsule v11.13 after the File_51a / File_55 public-clean control-registration update (June 27 2026, author-directed one-line pointer update; no Style Guide rules, terminology standards, Machine Guards, claim-status labels, arithmetic controls, or repository procedures changed); companion-control pointers refreshed to Register v1.15 / Procedures v3.2 / Capsule v11.14 after the File_51b convention-entry update (June 27 2026, author-directed one-line pointer update; no Style Guide rules, terminology standards, Machine Guards, claim-status labels, arithmetic controls, or repository procedures changed); companion-control pointers refreshed to Register v1.17 / Procedures v3.2 / Capsule v11.15 after the File_50a compact convention-entry update (June 27 2026, author-directed one-line pointer update; no Style Guide rules, terminology standards, Machine Guards, claim-status labels, arithmetic controls, or repository procedures changed); companion-control pointers refreshed to Register v1.18 / Procedures v3.2 / Capsule v11.16 after the File_56 Creation Decade Protocol Finalization registration (July 2 2026, author-directed one-line pointer update; no Style Guide rules, terminology standards, Machine Guards, claim-status labels, arithmetic controls, or repository procedures changed); full change history: Repository_Change_Archive
Active companion controls: State_Vocabulary_Register v1.18 (per-file states, conventions, Machine Guards); Project_Procedures v3.2 (workflow); Restart Capsule v11.16 (chronology, anchors, operators); Repository_Change_Archive v1.4 (non-controlling history; last-attested edition — location and maintenance under author review June 11 2026)

**Derived from Files 51, 53, 54, File_00 final pressure-tested conventions, File_02 final pressure-tested Flood/SKL conventions, File_03 final File-map convention, the Repository Conformity Plan, File_21 final post-final pressure-tested controls, File_22 final post-final pressure-tested controls, File_25 final post-final pressure-tested Decimal Invariance controls, File_34 final post-final pressure-tested SKL / Berossus controls, and the machine-ingestion / state-safe retrieval refinement — May 2026**

This guide defines the canonical repository standard going forward. It is based primarily on the final revised form of File 51, with additional implementation controls drawn from the repository-wide conformity plan. The purpose is not merely cosmetic standardization. The purpose is to convert the repository into a consistent, AI-forward Markdown source system that preserves arithmetic precision, modal-state logic, theological restraint, and cross-file retrievability.

This guide governs the source text. WordPress, HTML, PDF, and DOCX versions are derived publication layers.

The operative editorial rule remains:

**clarify the logic, preserve the terminology, reduce compression, add no ornament.**

More specifically:

**when a paragraph moves between modal systems, chronological traditions, node-classes, arithmetic operators, or mirror protocols, restate the active state explicitly; do not rely on implied carryover.**

---

## 0. Scope and Rule Types

### 0.1 Derived rules

Derived rules are rules clearly evidenced in File 51 itself, especially in its handling of:

- modal states;
- node-classes;
- sign conventions;
- cross-axis arithmetic;
- exact half-year states;
- table framing;
- terminology discipline;
- source-text restraint.

### 0.2 House rules

House rules are added for repository-wide normalization in Markdown, even where File 51 implies the practice but does not formalize it. Examples include:

- Markdown as canonical source format;
- restrained Markdown syntax;
- explicit source/publication separation;
- file-level metadata blocks;
- claim-status labels;
- revision pass types;
- audit-note discipline;
- repository-wide dependency tracking.

### 0.3 Implementation rules

Implementation rules govern the process of revising older repository files into the current standard. These rules are procedural rather than stylistic. They define how each file should be audited, revised, risk-rated, and prepared for derived publication.

### 0.4 Editorial aim

The repository standard is:

- exact;
- spare;
- state-tagged where needed;
- human-readable;
- AI-forward;
- free of rhetorical inflation;
- structurally stable across future revision passes.

Precision outranks smoothness. If a sentence is difficult but precise, do not simplify it unless the underlying meaning is understood.

---

## 1. Canonical Source Format

### 1.1 Repository master format

All repository files should be maintained first in Markdown.

Markdown is the canonical source because it is:

- plain text;
- structurally explicit;
- easy to diff, search, chunk, and standardize;
- easy to convert later into publication formats;
- better suited for AI retrieval than visually formatted publication layers.

### 1.2 Markdown standard

Use restrained Markdown:

- headings with `#`, `##`, `###`, and `####`;
- plain paragraphs;
- plain Markdown tables;
- LaTeX math with `$...$` and `$$...$$`;
- no raw HTML unless absolutely necessary;
- no decorative formatting.

### 1.3 Source vs publication

The repository follows this model:

| Layer | Status | Function |
|---|---|---|
| Markdown | Authoritative source | Editing, revision, AI retrieval, source control |
| WordPress | Derived publication | Public-facing article format |
| HTML | Derived publication | Web presentation |
| PDF | Derived publication | Fixed-layout distribution |
| DOCX | Derived publication | Editable publication export |

Once Markdown normalization begins, WordPress should not be treated as the primary editing environment.

### 1.4 Conversion principle

Derived publication formats must preserve the Markdown source structure as closely as possible. Conversion must not silently rewrite terminology, arithmetic notation, state-language, section numbering, table framing, or claim-status labels.

---

## 1A. Standard File Header

### 1A.1 Required header fields

Each repository file should begin with a compact Markdown header block before the main title.

Required fields:

```markdown
File:
Title:
Status:
Primary domain:
Canonical source:
Revision basis:
```

Optional fields where useful:

```markdown
Traditions:
Primary anchors:
Related files:
Major operators:
Major modal states:
```

Recommended full form:

```markdown
File: File_53
Title: The Book of Jubilees as a 22-Fold Creation-Genealogy Witness
Status: Draft / Revised / Final
Primary domain: Comparative; Theological
Traditions: BJ; MT; SP; LXX
Canonical source: Markdown
Primary anchors: 3856 BC; 1406 BC; 1399 BC
Related files: File_51c; File_52a
Major operators: 25/23; 70/69; 300/299
Major modal states: Cainan expunged; restored 2nd Cainan; +30 Apparent Age
Revision basis: 490d Repository Style Guide v2.4
```

### 1A.2 Function of the header

The file header is informational. It must not replace the H1 title or numbered sections.

The header helps future AI retrieval by identifying:

- file identity;
- file status;
- active chronological domain;
- primary anchors;
- related files;
- major operators;
- major modal states;
- revision basis.

### 1A.3 Status field

Use one of the following status labels unless a local project requires a more specific label:

| Status | Meaning |
|---|---|
| Draft | Provisional file still open to structural revision |
| Revised | Conformed to current style but not final |
| Final | Stable source file unless later cross-file revision requires update |
| Audit only | Reviewed but not rewritten |
| Dependency blocked | Cannot be revised safely until missing dependencies are supplied |

### 1A.4 Primary domain and traditions

Use `Primary domain` for the file’s main analytical domain.

Preferred domain labels:

- Regular;
- Cumulative;
- Rounded;
- Mirror;
- Prime;
- Comparative;
- Calendar;
- Statistical;
- Theological;
- Methodological.

Use `Traditions` when the file specifically involves textual, chronological, or extra-biblical traditions.

Preferred tradition labels:

- MT;
- SP;
- LXX;
- BJ;
- SOR;
- SKL;
- Berossus.

Example:

```markdown
Primary domain: Comparative; Cumulative
Traditions: MT; SP; LXX; BJ
```

---

## 1B. File Map

### 1B.1 Purpose

A File map is a terse functional index placed near the top of a repository file when it improves AI retrieval.

It answers this question:

```markdown
Where is the relevant logic located in this file?
```

A File map should identify section function. Where useful, it may also identify active state, operator, node-class, or dependency status.

### 1B.2 Placement

Preferred placement:

```markdown
## 0. File-function
## 0.1 Working state register
## 0.2 File map
```

If the file does not use a working state register, place the File map immediately after `## 0. File-function`.

The File map should appear before the first dense argumentative or arithmetic section.

### 1B.3 Standard form

Preferred form for complex files:

```markdown
## 0.2 File map

| Section | Function | Active state / operator |
|---|---|---|
| §0 | File-function and state controls | file-level modal states |
| §1 | Main identity or thesis | active tradition/state |
| §2 | Core arithmetic or logic engine | stated operators |
| §3 | Verification or synthesis | arithmetic facts / structural inference |
| §4 | Cross-references and dependencies | dependency tracking |
```

Preferred form for short files:

```markdown
## 0.2 File map

| Section | Function |
|---|---|
| §0 | Defines file function and active states |
| §1 | Identifies the main figure, thesis, or file subject |
| §2 | Records the primary logic engine or harmonic anchors |
| §3 | Verifies stated dates and spans |
| §4 | Lists cross-file dependencies |
```

### 1B.4 Restraint rule

A File map is not a decorative table of contents.

Do not use it to:

- repeat every heading mechanically;
- summarize the file in prose;
- add rhetorical framing;
- replace the file header;
- replace the modal-state register;
- replace the cross-reference index.

Use it only when it improves retrieval, navigation, or state/operator recognition.

### 1B.5 AI-forward rule

The File map should be functional rather than literary.

Good File map entries use labels such as:

- `file-function`;
- `state controls`;
- `logic engine`;
- `arithmetic verification`;
- `claim-status control`;
- `cross-file dependencies`;
- `appendix-only material`.

Avoid vague entries such as:

- `Introduction`;
- `Background`;
- `Discussion`;
- `Conclusion`;

unless the local file actually uses those headings and their function is already clear.

---

## 1C. Machine-Ingestion and Derived AI Formats

### 1C.1 Canonical-source rule

The canonical repository source remains Markdown.

RAG indexes, Knowledge Graph records, JSON exports, JSONL fine-tuning datasets, prompt/response pairs, embedding metadata, and similar AI-facing formats are derived extraction layers.

Do not distort the Markdown source in order to imitate a future training dataset. The source file should remain a state-controlled repository file, not a synthetic dialogue transcript.

### 1C.2 State-safe retrieval

The repository is optimized for state-safe retrieval.

State-safe retrieval means that an AI system should be able to retrieve a paragraph, table, File map entry, Machine Guard, or appendix note without losing the governing state.

Where needed, a retrieved chunk should carry or sit near enough to identify:

- active state;
- chronological tradition;
- node-class;
- operator;
- claim-status;
- dependency source;
- main-body, appendix-only, Mirror, inverse, statistical, or exploratory status.

The chief ingestion risk is not merely poor retrieval. The chief risk is correct retrieval applied under the wrong state, operator, tradition, node-class, or claim-status.

### 1C.3 Metadata and extraction discipline

Stable headers, File maps, state registers, claim-status notes, and Machine Guards make the Markdown source extractable. They should be written for source clarity first and machine extraction second.

Do not require every file to carry unused optional metadata fields. Required header fields remain required. Optional fields should be included only when they improve retrieval, indexing, dependency recognition, or state recognition.

### 1C.4 JSON / JSONL derivation

If JSON, JSONL, Knowledge Graph triples, vector-index metadata, or prompt/response training pairs are produced later, they should be generated from the canonical Markdown source.

A later extraction script may map:

| Markdown source element | Possible derived AI element |
|---|---|
| File header | document-level metadata |
| File map | section-function index |
| Working state register | state ontology / node-class metadata |
| Machine Guard | negative constraint / non-collapse rule |
| Claim-status note | evidential-role metadata |
| Dependency note | dependency edge / blocked-inference flag |
| Arithmetic table | structured span / operator record |

This extraction should preserve source meaning. It must not silently rewrite arithmetic, anchors, modal states, node-classes, sign conventions, operators, Mirror protocols, inverse-number status, claim-status labels, or dependency boundaries.

Machine Guard [CANONICAL MARKDOWN / DERIVED AI FORMATS]:
Markdown is the canonical repository source. RAG indexes, Knowledge Graph records, JSON, JSONL, embedding metadata, and prompt/response training datasets are derived extraction layers. Do not reshape the source file into dialogue format, training-pair format, or generic AI-summary format if doing so weakens arithmetic precision, modal-state control, operator clarity, node-class distinction, claim-status control, or dependency boundaries.

---

## 2. Core Editorial Principles

### 2.1 No rhetorical inflation

State arithmetic facts directly. Do not intensify them rhetorically.

Avoid phrases such as:

- `proves beyond doubt`;
- `astonishing`;
- `incredible`;
- `undeniable`;
- `clearly designed`, unless the file truly establishes that level of claim.

Let arithmetic, factorization, recurrence, textual anchoring, and state-control carry the force of the argument.

### 2.2 Arithmetic facts vs interpretive statements

Arithmetic facts should be stated directly.

Structural inferences should use measured language such as:

- `suggests`;
- `is consistent with`;
- `appears to`;
- `is compatible with`;
- `supports the possibility that`;
- `functions as corroboration for`.

Statistical results should be described as:

- `occurs more frequently than expected`;
- `exceeds the baseline expectation`;
- `is statistically notable under the stated test`.

Statistical results should not be described as proving authorial intent by themselves.

### 2.3 Theological restraint

Standard, non-controversial theological observations within the biblical and Christian tradition may be stated directly when they are not the sole support for a mathematical or structural claim.

More specialized, disputed, or structurally load-bearing theological interpretations should use measured language.

### 2.3a Theological and typological note preservation

Theological, typological, and symbolic observations should not be deleted merely because they are not mathematical. The repository’s numerical arguments often require theological framing in order to explain why a number, span, node, or recurrence matters.

The rule is therefore not removal, but classification.

When theological material is:

- textually anchored;
- necessary to explain the meaning of a numeric structure;
- coherent with the file’s active biblical or extra-biblical source;
- not being used to replace arithmetic proof;

it should be preserved as a labeled note, aside, or subsection.

Preferred labels:

- `Theological note:`
- `Typological note:`
- `Symbolic note:`
- `Canonical note:`
- `Reception-history note:`

Use these notes to preserve theological meaning while preventing the theological claim from silently carrying the arithmetic burden.

````markdown
Correct:

```markdown
Typological note:
The 22 × 490 structure visually resonates with Revelation's Alpha-Omega, First/Last, and Beginning/End language. This note explains the theological fit, but the arithmetic basis remains the outer Luke rail span and the overlapped middle generation. Additional source backgrounds require local source-control if opened.
```
````

### 2.4 Do not revise what is not understood

If a sentence is difficult but precise, do not simplify it unless the underlying meaning is clear.

If a value appears inconsistent, do not silently correct it. Mark it with an audit note.

### 2.5 Compression vs clarity

The repository may use dense technical prose. The aim is not to make every file elementary. The aim is to make each file explicit enough that a competent human reader and an advanced AI system can identify:

- active state;
- node-class;
- arithmetic operator;
- chronological tradition;
- claim-status;
- dependency structure.

---

## 2A. Editorial Layers and the Consolidated Workflow

### 2A.0 Workflow form

Under Project Procedures v3.0, repository normalization proceeds in three turns per file, not six sequential passes:

1. **Pass 0 — Intake + Mechanical Lint**: File Intake Sheet, risk rating, deterministic lint report, section-level revision plan. No revision occurs.
2. **Pass 1 — Unified Revision Pass**: one controlled rewrite applying all five editorial layers below, section by section, under all content invariants.
3. **Pass 2 — Verification Pass**: machine diff between source and revision; audit of every change by class; scripted arithmetic recheck where parseable; consolidated Author-Decision list.

Finalization remains a separate author-invoked act. High-risk files split Pass 1 once (layers 1–3, then layers 4–5). The five layers below are no longer separate passes; they are the checklists the Unified Revision Pass must satisfy simultaneously, and the audit classes the Verification Pass confirms.

### 2A.1 Structural layer

Correct heading hierarchy, section numbering, appendix placement, table framing, file-map placement, and Markdown source structure.

When a File map improves AI retrieval, add it. Keep it terse, functional, and state-aware. Do not use it as a decorative table of contents. Complete the machine-ingestion check where applicable.

Checklist:

```markdown
Structural layer satisfied:
- headings normalized
- section hierarchy corrected
- appendices nested correctly
- tables identified
- file header added
- File map added or confirmed unnecessary
- machine-ingestion check completed where applicable
```

### 2A.2 Terminology layer

Normalize repository terms, capitalization, hyphenation, node-class language, modal-state labels, and cross-file references.

Checklist:

```markdown
Terminology layer satisfied:
- number formatting normalized
- BC/AD formatting normalized
- repository terms capitalized
- technical compounds normalized
- local file-reference style preserved
```

### 2A.3 Modal-State layer

Audit modal states, node-classes, sign conventions, slash-pairs, ranges, display labels, and mirror protocols.

Checklist:

```markdown
Modal-State layer satisfied:
- modal states preserved
- node-classes tagged
- sign conventions defined
- slash-pairs/ranges clarified
- no display label substituted for computational state
```

### 2A.4 Arithmetic layer

Verify same-side spans, cross-axis spans, exact ratios, date ranges, half-year states, Key-of-23 conversions, and undefined operator dependencies.

Checklist:

```markdown
Arithmetic layer satisfied:
- same-side spans checked
- cross-axis spans checked
- Key conversions checked
- exact halves preserved
- undefined dependencies flagged
- no computational rounding introduced
```

### 2A.5 Argument layer

Reduce rhetorical inflation, clarify claim-status, distinguish arithmetic facts from interpretive statements, and add state-tags where dense argumentation shifts systems.

Checklist:

```markdown
Argument layer satisfied:
- rhetorical inflation reduced
- claim status clarified
- weak material moved or labeled
- tables framed
- dense paragraphs decompressed without diluting precision
```

### 2A.6 Publication Pass

The Publication Pass remains a separate, later step. Prepare the conformed Markdown for WordPress or other derived publication formats without altering source terminology, arithmetic, or state-language.

Deliverable:

```markdown
Publication Pass Complete:
- Markdown source preserved
- publication formatting applied only at derived layer
- section numbers preserved
- tables preserved or safely converted
- no source terminology altered
```

Machine Guard [UNIFIED PASS INVARIANTS]:
Consolidating the layers into one pass does not relax any content invariant. Do not silently correct arithmetic. Do not alter anchors, modal states, node-classes, sign conventions, operators, Mirror protocols, or theological claims. Audit-note and dependency-note discipline, authorial-direction thresholds, and all namespace, firewall, and non-retrojection controls apply within the Unified Revision Pass exactly as they applied across the former sequential passes.

---

## 2B. Claim-Status Labels

### 2B.1 Purpose

When a file contains layered argumentation, use explicit claim-status language. This prevents the collapse of textual data, arithmetic facts, structural inference, authorial design, providential synchronization, and exploratory observation into one undifferentiated claim.

### 2B.2 Preferred labels

| Label | Meaning | Permitted function |
|---|---|---|
| Textual datum | Directly stated by the biblical or extra-biblical text | May support primary argument |
| Arithmetic fact | Computed directly from stated constants | May support primary argument |
| Structural inference | Follows from repeated patterning or aligned architecture | May support argument when adequately controlled |
| Probable authorial design | Likely intended by the human author or textual tradition | May support argument when textual and arithmetic controls are strong |
| Providential synchronization | Coherent pattern probably beyond demonstrable authorial intent | Corroborative unless file is explicitly theological or providential in scope |
| Statistical result | Output of a defined scan or measurable test | Corroborative unless the test is the subject of the file |
| Typological reading | Theological or literary correspondence between persons, events, or structures | May support argument when textually anchored |
| Exploratory note | Interesting but not load-bearing | Footnote or appendix material |
| Appendix-only | Useful but should not support the main argument | Appendix material only |
| Audit note | Possible error, dependency, or unresolved issue | Requires author decision |

### 2B.3 Primary burden rule

Do not allow providential, exploratory, statistical, or appendix-only material to carry the primary burden of proof unless the file explicitly announces that such material is the subject of investigation.

### 2B.4 Authorial vs providential distinction

When a pattern plausibly exceeds what can be attributed to an ancient author or tradition, label it as providential synchronization or structural overpattern rather than probable authorial design.

Correct:

```markdown
As an arithmetic fact, the span equals 2450. As a structural inference, this supports the claim that the BJ framework is built around a jubilee architecture. The later Mirror recurrence is better treated as providential synchronization or secondary corroboration, not as direct evidence of BJ authorial intent.
```

Incorrect:

```markdown
The Mirror recurrence proves that the author of Jubilees intended the later AD alignment.
```

### 2B.5 Restraint rule

Claim-status labels should be used where they clarify layered argumentation. They do not need to be attached to every sentence or every arithmetic fact.

Use explicit labels when:

- authorial intent and providential synchronization might be confused;
- appendix-only material might be mistaken for the primary argument;
- statistical or exploratory material appears near the main thesis;
- a file moves between textual datum, arithmetic fact, and structural inference.

Do not overload ordinary prose with unnecessary claim-status labels.

---

## 3. Heading Hierarchy

Use strict hierarchical nesting. Do not skip levels.

| Level | Markdown | Use |
|---|---|---|
| H1 | `#` | File title only |
| H2 | `##` | Major numbered sections: `1`, `2`, `3` |
| H3 | `###` | Subsections: `2.1`, `4A.7`, `A.1` |
| H4 | `####` | Sub-subsections: `2.3.1`, `14.1a` |

### 3.1 General rules

- A subsection must sit under its parent section.
- Bold text must not substitute for a heading.
- If content needs a section number, it needs a heading.
- Appendix sections such as `A.1` and `A.2` use H3 under an H2 appendix header.
- Do not use heading levels decoratively.

### 3.2 Alphanumeric branches

Lettered branches are valid and must still nest properly.

Examples:

- `4A`;
- `4A.1`;
- `7A`;
- `14.1a`;
- `14.8.1`;
- `A.1`.

### 3.3 One H1 rule

Each file should have one H1 title only. The file header may precede the H1 title, but it is not itself the title.

### 3.4 Appendix heading rule

Use appendices for material that is secondary to the main argument.

Preferred form:

```markdown
## Appendix A. Mirror Stress-Test Material

### A.1 First appendix subsection
```

---

## 4. Number Formatting

### 4.1 No commas in numbers

All numbers appear without commas.

Correct:

- `14006 BC`;
- `12600`;
- `258600`;
- `100000 iterations`.

Incorrect:

- `14006 BC`;
- `12600`;
- `258600`;
- `100000 iterations`.

This applies in:

- prose;
- tables;
- math;
- notes;
- captions;
- file headers;
- appendix material.

### 4.2 BC/AD formatting

Use:

- `4106 BC`;
- `AD 4105`.

Do not use:

- `4106BC`;
- `4106 B.C.`;
- `4106 BC`;
- `4105 AD`.

A-space values carry no BC/AD suffix:

- `A = −4105`.

### 4.3 Ranges and spans

Use an en-dash for ranges:

- `4121–4114 BC`;
- `4121.5–4114.5 BC`.

Use `to` in prose:

- `from 4106 BC to 1406 BC`.

Use `=` for span results:

- `4106 − 1406 = 2700`.

### 4.4 Exact halves

Half-year values are permitted only as exact `.5` values.

Examples:

- `2518.5 BC`;
- `4121.5–4114.5 BC`.

Do not introduce arbitrary decimal expansions. Only integers, exact halves, and exact rational expressions belong in the source unless a specific exact rational is intended.

### 4.5 Exact rationals

Exact rational expressions may be used where the repository system requires them.

Examples:

- `25/23`;
- `70/69`;
- `300/299`;
- `23/40`.

Do not replace exact rationals with rounded decimal approximations unless a derived explanatory note explicitly requires it.

### 4.6 Key-of-23 Residue Protocol

The normal Key-of-23 operators remain exact whole-year conversion ratios:

- `25/23`;
- `70/69`;
- `300/299`.

The Residue Protocol is a separate drift-to-day register. It is invoked only when a file explicitly shifts from ordinary whole-year Key-of-23 conversion to physical residue or conceptual residual-display.

When the Residue Protocol is active, use these working definitions:

```markdown
K = schematic Key-of-23 solar-equivalent year
S_K = calibrated solar year used by the Residue Protocol
R_23 = root physical residue per 23 solar years
```

The shared schematic year is:

```markdown
K = (25 × 336) / 23
K = (70 × 360) / 69
K = (300 × 364) / 299
K = 8400 / 23 = 365.217391304... days
```

The calibrated solar year used by the protocol is represented in exact working form as:

```markdown
R_23 = 23/40 day = 0.575 day
S_K = K + 1/40
S_K = 8400/23 + 1/40
S_K = 336023/920 = 365.242391304... days
```

Display rule:
The decimal `365.2423914` is a rounded display of `S_K`. Use `336023/920` where exact residue arithmetic is required.

The root block is:

```markdown
23 × S_K = 8400 + 23/40
23 × S_K = 8400.575 days
23S_K − 8400 = 23/40 = 0.575 day
```

General physical-residue formula:

```markdown
Residue over N solar years = N × (S_K − K)
Residue over N solar years = N / 40 days
```

For a Key-of-23 ratio `p/q`, where `p` is the schematic-calendar side and `q` is the calibrated solar-year side:

```markdown
Physical residue over q solar years = q/40 days
Conceptual residual-display = (q/40) × p/q = p/40 days
```

Compact register:

| Register | Operator | Physical residue | Conceptual residual-display |
|---|---:|---:|---:|
| Priestly | `25/23` | `23/40 = 0.575 day` | `25/40 = 0.625 day = 15 hours` |
| Prophetic | `70/69` | `69/40 = 1.725 days` | `70/40 = 1.75 days` |
| Enochian | `300/299` | `299/40 = 7.475 days` | `300/40 = 7.5 days` |
| Enochian side ratio | `294/293` | `19/920 ≈ 0.020652 day` | optional side-ratio display only; not a Key-of-23 residual-display constant |

Machine Guard [RESIDUE PROTOCOL]:
The residue formula does not replace ordinary Key-of-23 whole-number conversion. Use `25/23`, `70/69`, and `300/299` as exact rational operators for chronological conversion. Invoke residue arithmetic only where the file explicitly shifts from whole-year conversion to drift-to-day calculation. Distinguish physical residue from conceptual residual-display. Do not feed display constants such as `0.625`, `1.75`, `7.0`, `7.5`, or `175` back into ordinary date arithmetic as if they were civil-year spans. When `6.9 days` is displayed as `7.0 days`, the operation is residual day-year lift: `6.9 years × 70/69 = 7 years`, with `7` schematic years corresponding to `2520` days. It is not a physical residue-rounding rule.

### 4.7 Conceptual residual-display and residual day-year lift

Physical residue and conceptual residual-display are distinct node-classes.

| Value type | Definition | Function |
|---|---|---|
| Physical residue | Actual day-drift against `S_K`, computed as `N / 40 days` | Executable residue arithmetic |
| Conceptual residual-display | Physical residue passed through the same Key-of-23 ratio that governs the corresponding year conversion | Liturgical or day-year display; not physical drift |

The conceptual residual-display is not ordinary rounding. It is a day-year echo. Residue-days may echo the corresponding residue-years; therefore the same Key-of-23 operator may lift the display value even though the physical residue remains unchanged.

Example:

```markdown
276 / 40 = 6.9 physical residue-days
6.9 years × 70/69 = 7 years
7 × 360 = 2520 days
```

Therefore:

```markdown
6.9 physical residue-days → 7.0 conceptual residual-display days
```

The `175-day` display follows the same rule:

```markdown
25 × 276 = 6900 years
6900 / 40 = 172.5 physical residue-days
25 × 7.0 residual-display days = 175 residual-display days
```

Do not treat `175` as the physical residue over `6900` years unless the file explicitly defines a local operator that changes the active state from physical residue to residual day-year display.

---

## 5. Span Arithmetic

### 5.1 Same-side spans

When both dates lie on the same side of the BC/AD axis, compute by subtraction.

Examples:

- `4106 − 1406 = 2700`;
- `3486 − 1886 = 1600`.

### 5.2 Cross-axis spans

When the span crosses the BC/AD axis, use the repository-standard formula:

```markdown
BC + AD − 1
```

Example:

```markdown
4166 + 4115 − 1 = 8280
```

### 5.3 Do not mix operators

Do not apply same-side subtraction to cross-axis spans. Do not apply `BC + AD − 1` to same-side spans.

### 5.4 Civil-year note

The repository uses civil BC/AD reckoning with no year 0. This is why cross-axis spans use `BC + AD − 1`.

### 5.5 Audit categories for arithmetic

Every Arithmetic-layer check (within the Unified Revision Pass, or as a standalone Arithmetic Pass under the High-risk split) should cover at least these categories:

| Arithmetic type | Rule |
|---|---|
| Same-side BC span | subtraction |
| Same-side AD span | subtraction |
| Cross-axis BC/AD span | `BC + AD − 1` |
| Key of 23, Priestly | `25/23` |
| Key of 23, Prophetic | `70/69` |
| Key of 23, Enochian | `300/299` |
| Residue Protocol | only when explicitly invoked; physical residue uses `N / 40 days` |
| Residual-display constants | display-only unless a residual day-year lift operator is active |
| Exact halves | preserve `.5`; no decimal drift |
| Exact rationals | preserve rational form |
| Unknown operators | mark as defined in prerequisite file |

---

## 6. Terminology Standards

### 6.1 Capitalized system terms

Capitalize the following when used as repository terms:

- `Actual MT`;
- `Rounded Scaffold`;
- `Creation`;
- `Flood`;
- `Conquest`;
- `Exodus`;
- `Entry` when functioning as the Egypt-entry node;
- `Exile` / `Captivity` when functioning as fixed chronological nodes;
- `Key of 23`;
- `Residue Protocol` when functioning as the named Key-of-23 drift-to-day register;
- `+30 Apparent Age`;
- `+60 Terah`;
- `2nd Cainan` when functioning as a recognized variant-state label;
- `Book of Jubilees`;
- `BJ` when used as the repository abbreviation;
- `SKL` when used as the repository abbreviation for Sumerian King List;
- `Berossus`;
- `MT Minimum-Regular`;
- `MT Standard-Normal`;
- `Sumerian A / SKL Short`;
- `Sumerian B / SKL Long`;
- `+30 Apparent Mode`;
- `+2 local rail` when used as a formal SKL rail label;
- `+720 scale-state` when used as a formal SKL/Berossus scale label;
- `Flood Week` when used as a formal cumulative envelope label;
- `Mirror` when functioning as a named repository structure.

### 6.2 Lowercase technical terms

Prefer lowercase in prose for generic technical descriptors:

- `mod-5`;
- `mod-30`;
- `cross-tradition`;
- `cycle-family`;
- `node-class`;
- `cross-modal`;
- `boundary-state`;
- `phase-resolved`;
- `rounded-to-rounded`;
- `same-side`;
- `cross-axis`.

Capitalize these only at sentence start, in titles, or when part of a formal label.

### 6.3 Preferred terminology

Use:

- `actual` rather than `original` for unrounded MT states;
- `cross-tradition` for MT/LXX/SP comparative language;
- `patriarch` for ordinal sequence counting, as in `23rd patriarch`;
- `chronological tradition` for MT/SP/LXX/BJ/SOR-type systems;
- `state` for valid modal alternatives;
- `operator` for a defined mathematical procedure;
- `anchor` only when the date functions as an anchoring node.

### 6.4 Narrow rule on generation

Do not ban the word `generation` absolutely.

Use:

- `patriarch` for ordinal count;
- `generation` where the biblical generational concept is actually intended.

Correct distinction:

- `Joseph is the 23rd patriarch from Adam`;
- `Four generations of 110`.

### 6.5 Avoid vague substitutions

Do not replace precise repository terms with smoother but less exact synonyms.

Examples:

| Avoid | Prefer |
|---|---|
| original date | actual date, if unrounded MT is meant |
| symbolic date | rounded state, mirror target, or comparison state, as applicable |
| option | modal state, alternate state, or local comparison state |
| pattern | recurrence, structural alignment, span-family, or cycle-family |
| date | anchor, endpoint, boundary, block-member, or mirror target, where applicable |

### 6.6 Cainan / Kainan spelling

Use `2nd Cainan` as the default repository variant-state label unless a file has adopted a local spelling convention.

Use `Kainan` when:

- quoting or closely following a translation that uses `Kainan`;
- discussing BJ-specific narrative material where the file has explicitly adopted that spelling;
- preserving the author’s local terminology.

Use `Cainan expunged` and `restored 2nd Cainan` as standard state labels unless the local file defines otherwise.

If both spellings appear in one file, define the convention on first use.

### 6.7 File_02 Flood and SKL terminology

The following terms are repository-wide labels after the `File_02` Flood/SKL update.

| Term | Meaning | Handling |
|---|---|---|
| `MT Minimum-Regular` | Forward-most regular MT comparison position under the 215-year Egypt span | Use for 2243 BC Flood and 3899 BC Creation endpoint states |
| `MT Standard-Normal` | Normative operating MT state under full 430 years in Egypt, without `+60 Terah` | Use for 2458 BC Flood and 4114 BC Creation endpoint states |
| `MT Standard-Normal +60` | Standard-Normal state with `+60 Terah` applied | Use for 2518 BC Flood and 4174 BC Creation endpoint states |
| `cumulative Flood Week` | Week-of-years envelope in cumulative chronology | Use for `4836–4829 BC` and `5296–5289 BC` states |
| `judgment-week envelope` | AD-side civil counterpart to the cumulative Flood Week | Use for `AD 65–72`, with AD 70 as internal event-target |
| `Sumerian A / SKL Short` | SKL state using the 17980-year total for 23 kings | Main `File_02` SKL display state |
| `Sumerian B / SKL Long` | SKL state using the 24510-year total for 23 kings | Alternate SKL state, shifted by the 6480-year variant |
| `+30 Apparent Mode` | SKL mode rail shifting the whole beginning-and-anchor pair by 30 years | Applicable to SKL Short and SKL Long |
| `+2 local rail` | Local two-year SKL shift of the beginning-and-anchor pair | Related to but not interchangeable with `+720 scale-state` |
| `+720 scale-state` | Cosmic SKL/Berossus expression of the +2 pattern through 720 days / years | Must be declared explicitly when active |
| `whole-year total` | SKL total used for local arithmetic | Use for `17980` and `24510` when the month/day appendage is dependency-controlled |
| `appended month/day textual datum` | SKL phrase `3 months and 3.5 days` preserved in addition to whole-year totals | Full function remains dependency-controlled by `File_34` |

Avoid bare `MT Regular` when the file requires the distinction between `MT Minimum-Regular` and `MT Standard-Normal`. Avoid bare `Sumerian A` or `Sumerian B` without defining whether the active label means SKL Short or SKL Long.

---

## 7. Hyphenation Rules

Technical compounds are normally hyphenated when used adjectivally.

Examples:

- `pre-Flood`;
- `post-Flood`;
- `cross-axis`;
- `boundary-state`;
- `phase-resolved`;
- `rounded-to-rounded`;
- `same-side`;
- `cross-modal`;
- `node-class`;
- `cycle-family`;
- `Creation-week`;
- `source-text`;
- `file-level`;
- `cross-file`;
- `state-tagged`;
- `AI-forward`.

### 7.1 Creation-week

Use `Creation-week` as the standard adjectival compound.

Do not vary it as:

- `Creation week`;
- `creation-week`;
- `Creation Week`;

unless grammar strictly requires another form.

### 7.2 Mod compounds

Use:

- `mod-5`;
- `mod-30`;
- `mod-210`.

Do not use:

- `mod 5`;
- `mod5`;
- `Mod-5`, unless at sentence start or in a formal title.

---

## 8. Sign Conventions

### 8.1 Sign conventions are local, not global

A file may contain more than one valid sign convention. When a convention changes, it must be explicitly defined at the point of use.

Examples:

- `Scaffold → Actual MT`;
- `Shift = Rounded BC − Actual BC`.

Do not assume one implicit convention for the whole file.

### 8.2 Standard phrasing

When adjustments are described, use direct notation such as:

- `Scaffold → Actual MT`;
- `Rounded + Adjustment = Actual MT`;
- `4(+2) + 2(−1) = +6`.

If a sign rule reverses in a later table, say so explicitly.

### 8.3 Sign convention table framing

Any table with a non-obvious sign convention must include a short framing note immediately before the table.

Example:

```markdown
The following table uses `Shift = Rounded BC − Actual BC`. Positive values therefore indicate that the rounded state is earlier than the actual state in BC reckoning.
```

---

## 9. Modal States and Node-Classes

This is one of the central repository standards.

### 9.1 Preserve modal states

When two or more valid chronological states coexist, preserve them as states. Do not collapse them into one `correct` value unless the file explicitly requires that.

Use language such as:

- `simultaneous, non-competing modal states`;
- `must not overwrite`;
- `preserve as modal states per domain`;
- `do not reconcile`;
- `working state in this file`;
- `alternate local option`.

Avoid language such as:

- `the correct date is`;
- `this replaces`;
- `this supersedes`;

unless replacement is genuinely intended.

### 9.2 Distinguish node-classes

Do not collapse different node-classes merely because their numerical values are related.

Examples of distinct node-classes:

- endpoint;
- anchor;
- boundary;
- block;
- envelope;
- spread;
- mirror target;
- modal overlap node;
- comparison state;
- hinge;
- bridge;
- trunk;
- branch;
- pillar;
- register;
- control node.

A file should identify the node-class clearly on first use when confusion is possible.

### 9.3 State-tag persistence

In dense paragraphs, restate the active state whenever the text shifts system, layer, or node-class.

Examples of shifts requiring renewed tagging:

- rounded → actual;
- regular → cumulative;
- base → `+60`;
- base → `+30`;
- MT → SP → LXX;
- transmitted SP → alternate SP;
- Year-6 anchor → comparison state;
- boundary → endpoint;
- same-side arithmetic → cross-axis arithmetic;
- authorial claim → providential synchronization.

Do not rely on implied carryover in dense argumentation.

### 9.4 New subsection rule

Do not assume state continuity across subsection boundaries. On first use in a new dense subsection, restate the relevant state, node-class, or sign convention.

### 9.5 Modal-state table

When several modal states are active, a compact table is preferred.

Example:

| State | Date | Function in file | Adopted? |
|---|---:|---|---|
| Actual MT | 4116 BC | Year-6 anchor | Yes |
| Rounded Scaffold | 4106 BC | Rounded Creation anchor | Yes |
| +60 Terah | 4166 BC | Variant comparison state | Local only |
| +30 Apparent Age | 4136 BC | Apparent-age overlay | Secondary |

### 9.6 Minimum-Regular and Standard-Normal states

Some files require two simultaneous uses of regular MT terminology. The `File_02` standard is:

| State | Date example | Function |
|---|---:|---|
| `MT Minimum-Regular` | Flood 2243 BC | Forward-most regular MT comparison state |
| `MT Minimum-Regular +60` | Flood 2303 BC | Minimum-Regular plus `+60 Terah` |
| `MT Standard-Normal` | Flood 2458 BC | Normative operating state; full 430 Egypt; no `+60 Terah` |
| `MT Standard-Normal +60` | Flood 2518 BC | Standard-Normal plus `+60 Terah` |

Machine Guard [MT MINIMUM / STANDARD-NORMAL]:
Do not collapse `MT Minimum-Regular` and `MT Standard-Normal` into bare `MT Regular`. The minimum state may be the forward-most comparison position, while the standard-normal state may be the normative operating date. Identify which state is active before computing.

### 9.7 SKL Short / Long and scale-state rails

When a file uses the Sumerian King List as a chronological witness, preserve the SKL state and rail.

| State | Whole-year total | Anchor | Beginning |
|---|---:|---:|---:|
| `Sumerian A / SKL Short, Physical` | 17980 | 2906 BC | 20886 BC |
| `Sumerian B / SKL Long, Physical` | 24510 | 2856 BC | 27366 BC |

Rail labels:

| Rail | Function |
|---|---|
| `Physical` | Base SKL beginning-and-anchor state |
| `+30 Apparent Mode` | Global SKL mode rail shifting the beginning-and-anchor pair by 30 years |
| `+2 local rail` | Local two-year shift of the beginning-and-anchor pair |
| `+720 scale-state` | Cosmic SKL/Berossus expression related to `+2` through `2 years = 720 days` |

Machine Guard [SKL +2 / +720 SCALE-STATE]:
The SKL `+2 local rail` and the SKL/Berossus `+720 scale-state` are related scale states, not interchangeable arithmetic operators. Apply `+2` directly only when the local SKL beginning-and-anchor pair is active. Declare the `+720` or `±720` scale-state explicitly when operating in the cosmic SKL/Berossus grid.

### 9.8 Rounded Scaffold methodological status

The Rounded Scaffold is a methodological and geometric deduction built on the back of the actual chronologies. It is not a literal chronology of MT, SP, LXX, BJ, SOR, SKL, or Berossus.

Before `File_51a` or another file that explicitly opens the Rounded Scaffold, references to Rounded Scaffold values should be clarity-only forward references. They may distinguish a rounded methodological state from normal chronological states, but they must not make the Rounded Scaffold carry the literal chronological argument.

Example:

| Date-label | State | Handling |
|---|---|---|
| Joseph 1915–1805 BC | Standard 1876 BC Entry state | Literal active Joseph chronology |
| Joseph 1916–1806 BC | Rounded Scaffold state | Methodological mod-5 state; clarity-only before `File_51a` |

Machine Guard [ROUNDED SCAFFOLD STATUS]:
The Rounded Scaffold is a methodological deduction and comparison layer, not a literal chronology of MT, SP, LXX, BJ, SOR, SKL, or Berossus. Before `File_51a` opens the Rounded Scaffold directly, cite Rounded Scaffold values only to prevent state confusion. Do not let rounded values overwrite actual, standard, BJ, SOR, or tradition-specific chronology.

### 9.8a Rounded Scaffold non-retrojection

The Rounded Scaffold / rounded root chronology is the `File_51a` methodological mod-5 layer. It must not be retrojected into earlier repository files or into ordinary actual chronology states unless a local section explicitly opens the `File_51a` Rounded Scaffold state.

Default rule:
Regular chronology, cumulative chronology, comparative textual chronology, SKL chronology, Mirror displays, calendar states, prophetic span displays, and local 10x scale-states remain actual / local-state chronologies unless the local file explicitly opens the Rounded Scaffold state.

Clean values, mod-10 displays, 10x scale-states, Mirror displays, SKL mod-10 displays, harmonically regular values, or apparently rounded values are not thereby File_51a Rounded Scaffold values. A clean number is not automatically a rounded number.

File_22 control example:
The `9890` cumulative-to-regular MT Creation bridge is actual chronology in `File_22`. The File_51a rounded counterpart is `9900`, a separate rounded chronology state. The two values may be compared, but one must not replace the other.

Machine Guard [ROUNDED SCAFFOLD NON-RETROJECTION]:
Do not identify clean, mod-10, harmonically regular, Mirror, SKL mod-10, 10x-scaled, or apparently rounded values with the File_51a Rounded Scaffold unless the local section explicitly opens that state. File_22's `9890` Cumulative-Regular Decimal Bridge is actual chronology. The `9900` rounded counterpart belongs to the later Rounded Scaffold state.

---

## 10. Exact States vs Display Labels

### 10.1 Computational state vs display label

When a half-year or phase-resolved value exists, preserve the exact computational state internally and distinguish it from its display label.

Example:

- computational state: `2518.5 BC`;
- display label: `Tishri 2519 BC`.

### 10.2 Rule

Exact states govern arithmetic. Display labels govern presentation.

### 10.3 Safeguard

Display labels must not be fed back into computation as replacement states.

### 10.4 Phase-resolved caution

If a date is phase-resolved, identify whether the file is using:

- Tishri reckoning;
- Nisan reckoning;
- midpoint-pivot logic;
- display-only labels;
- exact computational values.

### 10.5 Calendar-state suffixes: `n` and `t`

The suffixes `n` and `t` are calendar-state display labels. They are part of the modal state and must not be removed during arithmetic verification.

Standard meanings:

| Suffix | Meaning | Function |
|---|---|---|
| `n` | Nisan-state label | Spring / Nisan display state where the file marks the date explicitly |
| `t` | Tishri-state label | Fall / Tishri display state where the file marks the date explicitly |

Examples:

- `2460n BC`;
- `1959t–1955n BC`;
- `AD 1952t–1955n`.

Nisan remains the default state when no suffix appears, unless the local file explicitly defines a different default. Tishri remains valid where stated.

A suffixed date is not automatically an exact `.5` computational state. Exact half-year values govern arithmetic only when the file states an exact `.5` value or defines a phase-resolved computation. Otherwise, `n` and `t` remain display labels and modal-state identifiers.

Machine Guard [CALENDAR SUFFIXES]:
Do not strip `n` or `t` from a date label during revision. Do not convert `n` or `t` into `.5` arithmetic unless the file explicitly defines the exact phase-resolved value. Treat suffixed dates as calendar-state display labels until a local operator converts them into computational states.

---

## 11. Slash-Pairs, Ranges, Blocks, and Envelopes

These forms are not interchangeable.

### 11.1 Slash-pairs

Use slash-pairs for paired states such as:

- `4416/4411 BC`;
- `1406/1401 BC`.

A slash-pair is not an ordinary alternative. It usually represents an ordered pair of block-members, boundary states, or parallel endpoints.

### 11.2 Order matters

Do not reverse a slash-pair casually. If the pair represents upper/lower, earlier/later, or two fixed boundary members, preserve the ordering.

### 11.3 En-dash ranges

Use en-dash ranges for continuous spans or envelopes such as:

- `4121–4114 BC`;
- `4121.5–4114.5 BC`.

### 11.4 Block language

If a slash-pair functions as a named block, say so explicitly:

- `SP rounded Creation block: 4416/4411 BC`.

### 11.5 Envelope language

If a range functions as an actual or phase-resolved envelope, say so explicitly:

- `actual base Creation-week envelope: 4121–4114 BC`;
- `spread envelope: 4121.5–4114.5 BC`.

### 11.6 Slash-pair audit rule

When revising a slash-pair, check:

- whether the order is meaningful;
- whether both members are active;
- whether one member is upper/lower;
- whether one member is transmitted/alternate;
- whether the pair is a block, boundary pair, or comparison pair.

### 11.7 Full slash-pair display for compressed source forms

Compressed slash-pair shorthand is error-prone for AI parsing. When revising older files, expand compressed slash-pair forms into full endpoint display unless the local file explicitly requires the compressed form as a source-history label.

Example:

```markdown
Source shorthand: 13997/6 BC
Preferred revised display: 13997/13996 BC
```

The full display preserves both members of the pair and prevents the second member from being misread as `6 BC`, as a range endpoint, or as a typographical remnant.

### 11.8 Slash-pair plus Mirror target safety

When a slash-pair is paired with an AD Mirror target, do not automatically treat the slash-pair as an executable civil-span endpoint.

Required classification:

| Form | Required handling |
|---|---|
| `13997/13996 BC → AD 14000` | classify whether the pair is a Mirror display, adjusted cumulative state, endpoint pair, boundary pair, or executable span |
| `13997/13996 BC` alone | preserve as slash-pair; do not average; do not collapse; do not reverse order |
| compressed source form such as `13997/6 BC` | preserve only as source-history unless the file explicitly retains the shorthand |

If the file asserts a civil cross-axis span from a slash-pair to an AD date, check each member component-wise with `BC + AD − 1`.

Example:

```markdown
13997 + 14000 − 1 = 27996
13996 + 14000 − 1 = 27995
```

If the claimed span does not follow from the component-wise civil calculation, do not introduce a second missing-year operator. Add an `Audit note:` or classify the expression as a Mirror display / adjusted state until the governing target-generation protocol is supplied.

Machine Guard [SLASH-PAIR SAFETY]:
A slash-pair is not a range, average, or loose alternative. When paired with a Mirror target, identify the node-class before computing. Civil spans still use `BC + AD − 1`; Mirror target generation, A-space display, and adjusted cumulative display are separate protocols.

### 11.9 Flood Weeks and judgment-week envelopes

A cumulative Flood Week is an envelope, not a single-year anchor and not an inclusive ordinal count unless the local file explicitly defines such a count.

| Form | Node-class | Handling |
|---|---|---|
| `4836–4829 BC` | base rounded cumulative Flood Week | Preserve as a week-of-years envelope |
| `5296–5289 BC` | restored cumulative 2nd Cainan Flood Week | Preserve as the `+460` shifted week-of-years envelope |
| `AD 65–72` | judgment-week envelope | AD-side civil counterpart; AD 70 may be an internal event-target |

Civil cross-axis checks from a Flood Week to a judgment-week envelope must be computed component-wise using `BC + AD − 1`.

Example:

```markdown
4836 + 65 − 1 = 4900
4831 + 70 − 1 = 4900
4829 + 72 − 1 = 4900
```

Do not rewrite the statement as a single-point claim such as `4836 BC → AD 70 = 4900` unless the interior event-target state has been declared.

---

## 12. Machine Guard Format

### 12.1 Base form

Machine Guards normally begin with:

```markdown
Machine Guard [LABEL]:
```

### 12.2 Label format

- `Machine Guard` = two words, capitalized;
- label in square brackets;
- label normally in all caps;
- colon after the closing bracket.

### 12.3 Allowed extension

A Machine Guard may be followed by optional metadata lines where useful, such as:

- `Status:`;
- `Classification:`;
- `Scope:`;
- `Applies to:`.

The opening line should remain standardized.

### 12.4 Prose rule

The directive body should normally remain in prose rather than bullets unless sequential logic truly requires a list.

### 12.5 Examples of labels already in use

- `[JOSEPH EXPLICIT-DERIVATION]`;
- `[JOSEPH HARD-DEDUCTION]`;
- `[MODAL STATE]`;
- `[MOD-5 THEORETICAL]`;
- `[METHUSELAH BIFURCATION]`;
- `[COMPOSITE ALIGNMENT]`;
- `[CROSS-MODAL MIRROR]`;
- `[LIFESPAN VS. CHRONOLOGY FIREWALL]`;
- `[CALENDAR SUFFIXES]`;
- `[SLASH-PAIR SAFETY]`;
- `[RESIDUE PROTOCOL]`.

### 12.6 Machine Guard function

A Machine Guard is not rhetorical emphasis. It is a source-control device used to prevent future AI systems or human editors from collapsing a critical distinction.

Use Machine Guards sparingly.

---

## 13. Table Conventions

### 13.1 General table style

Use plain Markdown tables. Keep them readable and structurally simple.

### 13.2 Preferred abbreviations in tables

Abbreviations are acceptable in tables:

- `Act.`;
- `Rnd.`;
- `Adj.`;
- `Beg.`;
- `Cum.`;
- `Reg.`;
- `Diff.`;
- `Span`;
- `Anchor`.

In prose, spell out the full word unless brevity is clearly preferable.

### 13.3 Table framing rule

Any table using a non-obvious sign convention, state-layer, or comparison basis should be introduced by a one- or two-sentence framing note immediately before the table.

This framing note should identify as needed:

- sign convention;
- active state;
- methodology;
- scope;
- whether the table is actual, rounded, cumulative, theoretical, comparative, or audit-only.

### 13.4 Table notes

Table notes should sit immediately below the table.

Use:

```markdown
*Joseph’s lifespan of 110 is retained here as a textual datum rather than recalculated as a rounded scaffold value.*
```

Do not bury the note far from the table it qualifies.

### 13.5 Wide tables

Very wide tables should be simplified where possible. If a table becomes too wide for stable Markdown use, split it into smaller tables rather than forcing excessive width.

### 13.6 Alignment

Markdown itself does not strongly control visual alignment across platforms. Semantic clarity matters more than visual precision. Numeric columns may be right-aligned in Markdown syntax where supported, but this is secondary.

### 13.7 Required table audit

During revision, check whether each table has:

- clear active state;
- clear sign convention;
- clear column labels;
- no hidden operator shift;
- no display label substituted for computational state;
- no comma-formatted numbers;
- no ambiguous slash-pairs.

---

## 14. Standard Note Labels

Recurring note labels should be kept consistent.

Common labels:

- `Note:`;
- `Methodology:`;
- `Observation:`;
- `Footnote (...)`;
- `Cycle frequency note:`;
- `Cross-reference note:`;
- `Epistemological note:`;
- `Audit note:`;
- `Claim-status note:`;
- `Appendix note:`;
- `Publication note:`.

### 14.1 Rule

Use these labels only when they genuinely identify the function of the paragraph. Do not multiply labels unnecessarily.

### 14.2 Statistical note label

When a section documents a span also flagged by scan material, the preferred opener is:

```markdown
Cycle frequency note:
```

This is a preferred formula, not a mandatory heading.

### 14.3 Audit note label

Use `Audit note:` when a value, operator, state, or dependency appears uncertain.

Preferred form:

```markdown
Audit note:
This value appears inconsistent with [specific rule/calculation]. Do not revise silently. Requires author decision.
```

---

## 15. Cross-References

### 15.1 Internal references

Use section references in the form:

- `§4A.7`;
- `§14.1a`;
- `§16.2`.

For ranges:

- `§§4.2–4.5`;
- `§§A.1–A.4`.

### 15.2 Parenthetical form

Use:

- `(see §7.4)`;
- `(§3.4 methodology)`.

### 15.3 Cross-file references

At present the repository shows a mixed but stable pattern such as:

- `File 11`;
- `File 31`;
- `Files 50a–50e`;
- `File_51_Supplement_A`;
- `File_51_Supplement_B`.

Do not impose a different naming pattern unless the repository is formally normalized later.

### 15.4 Local preservation rule

Until formal normalization is undertaken, preserve the local file-reference style already in use in the source being edited.

### 15.5 Cross-file update note

When a revision creates a dependency or changes how a later file should refer to an earlier file, record this in a revision log.

Preferred form:

```markdown
Cross-file update needed:
File_52c should reference the revised definition of Protocol 1 in Style Guide v2 §18.3.
```

---

## 16. Citation Style

### 16.1 Biblical citations

Keep biblical citations compact and consistent.

Preferred styles:

- `Genesis 41:46`;
- `Gen 41:46`;
- `Dan 12:11`;
- `(Gen 41:46)`;
- `(Dan 12:11)`.

Use the same book-form consistently within a file or section. Do not mix full and abbreviated forms without reason.

### 16.2 Extra-biblical citations

Use similarly compact forms for extra-biblical texts:

- `1 Enoch 6`;
- `Jubilees 1:1`;
- `Seder Olam Rabbah`;
- `SOR` when used as the repository abbreviation for Seder Olam Rabbah;
- `Berossus`;
- `Sumerian Kings List`.

### 16.3 Multiple references

Group multiple references clearly and sparingly:

- `(Gen 41:46; 41:53; 45:6)`;
- `(Exod 12:40; Gal 3:17)`.

### 16.4 Use

Citations should support the chronological or textual claim directly. Do not over-cite simple arithmetic once the underlying textual constants have already been established.

### 16.5 Repository citations

When citing other repository files, preserve the local file-reference style unless the repository later adopts a formal citation system.

---

## 17. Mathematical Notation

### 17.1 Inline math

Use `$...$` for inline LaTeX where needed:

- `$n$`;
- `$1 - n$`;
- `$130 \times 3$`.

Simple arithmetic may remain in plain text when perfectly clear:

- `130 × 3 = 390`.

### 17.2 Display math

Use `$$...$$` for standalone equations:

```latex
$$2580 = 6 \times 430 = 2 \times 1290$$
```

### 17.3 Multiplication

Use `\times` in LaTeX and `×` in ordinary prose or math text.

Do not use:

- `x`;
- `*`;

except where code literally requires it.

### 17.4 Labels in math

Use `\text{}` inside LaTeX labels:

```latex
$Joseph_{\text{Entry}}$
```

### 17.5 Factorization style

Use:

- `23 × 360`;
- `6 × 460`;
- `70 × 7²`;
- `(= 60 × 23)`.

Superscripts should remain true superscripts where possible:

- `5³`;
- `40²`;
- `70²`.

### 17.6 Exact ratio notation

Use exact ratio notation for repository conversions:

- `25/23`;
- `70/69`;
- `300/299`.

Do not convert these ratios into approximated decimal values unless the approximation is itself being discussed.

### 17.7 Equation density rule

When more than three equations occur in sequence, consider using a table or a short explanatory sentence before the equations.

Dense equation clusters should remain readable and should identify the active anchor, state, or operator before computation begins.

---

## 18. Mirror Protocols and Span Operators

### 18.1 One cross-axis span formula

The repository uses one standard formula for cross-axis spans:

```markdown
BC + AD − 1
```

### 18.2 Separate the span formula from mirror-generation protocol

This distinction is critical.

There is:

- one cross-axis span operator;
- more than one admissible mirror-generation protocol.

Do not blur them together.

### 18.3 Protocol names

Use:

| Protocol | Definition | Function |
|---|---|---|
| Protocol 1 | Pure rounded A-space integer mirror | Used for rounded mirror generation |
| Protocol 2 | Tishri/Nisan phase mirror, midpoint-pivot | Used for phase-resolved mirror generation |

Whenever a cross-axis calculation appears, specify which protocol is active if the context does not make it obvious.

Use phrasing such as:

- `under Protocol 1`;
- `using the Protocol-2 phase mirror`.

### 18.4 Mirror local-burden rule

In a non-Mirror-focused file, Mirror results normally should not carry the local burden of proof for a claim that can be established internally by same-side arithmetic, textual data, or file-defined chronological states.

This does not mean the Mirror is intrinsically secondary in the repository system. It means the local file should first establish its own internal structure before using the Mirror to complete, confirm, or extend that structure.

Correct:

```markdown
The internal BJ span of 2450 establishes the primary local structure. The later Mirror recurrence is then classified by function: Mirror coordinate-completion if it completes the active coordinate field, Mirror corroboration if it stress-tests the established structure, or Mirror providential synchronization if it extends beyond demonstrable authorial intent.
```

Incorrect:

```markdown
The Mirror recurrence is the first proof that the BJ span is meaningful.
```

### 18.5 Mirror claim-status and coordinate-completion

The Mirror is not intrinsically secondary in the repository system. It is secondary only with respect to the local burden of proof in files whose primary topic is not Mirror mechanics.

The repository distinguishes three questions:

| Question | Rule |
|---|---|
| Does the local file’s main thesis require the Mirror in order to stand? | Usually no, unless the file is Mirror-focused. |
| Does the Mirror belong to the whole system’s coordinate architecture? | Yes. The Mirror functions as a cross-axis coordinate field of the repository. |
| Should every Mirror recurrence appear in the main body? | No. Placement depends on whether the Mirror result completes the active coordinate structure or merely adds corroboration. |

When Mirror material appears outside a Mirror-focused file, identify its role using one of the following labels:

| Label | Meaning | Placement |
|---|---|---|
| Mirror primary | Mirror mechanics are the subject of the file | Main body |
| Mirror coordinate-completion | The Mirror supplies the cross-axis counterpart needed to understand the full coordinate identity of a node, block, rail, or state | Main body or controlled synthesis section |
| Mirror corroboration | The Mirror confirms or stress-tests a structure already established by same-side or internal evidence | Main body if concise; appendix if extensive |
| Mirror providential synchronization | The Mirror coherence appears beyond demonstrable authorial intent | Main body only if system-relevant; otherwise appendix |
| Mirror exploratory note | The Mirror result is suggestive but not yet system-controlled | Appendix or audit note |
| Mirror appendix-only | The Mirror result is useful but not needed for the local argument or coordinate-completion | Appendix |

Mirror material should not be dismissed as decorative or merely secondary. In a whole-system view, the Mirror is analogous to the second axis in a coordinate plane. A same-side chronological structure may be analyzed independently, but the full repository architecture may require the mirrored/counter-axis in order to disclose the complete pattern.

Therefore, avoid blanket statements such as:

`Mirror material is secondary / appendix-only.`

Prefer:

`In this non-Mirror file, Mirror material does not carry the local burden of proof. Where it completes the coordinate structure, it is classified as Mirror coordinate-completion. Where it only confirms or extends the established structure, it is classified as Mirror corroboration or appendix-only material.`

### 18.6 Mirror vs inverse-number material

Mirror material and inverse-number material are not equivalent.

The Mirror functions as a cross-axis coordinate field of the repository. It may be required for full-system interpretation even when it is not required to prove the local thesis of a non-Mirror file.

The inverse-number operator is a derived transformation. It reverses base-10 digit structures and tests whether a span, node, or trunk preserves coherence under inversion. Unless a file is explicitly inverse-focused, inverse material should normally remain appendix-only or secondary corroboration.

| Structure | System role | Default handling outside focused files |
|---|---|---|
| Mirror | Cross-axis coordinate field | May appear in the main body as Mirror coordinate-completion or Mirror corroboration |
| Inverse-number operator | Derived transformation / diagnostic | Usually appendix-only unless the file is inverse-focused |
| Statistical scan | Exploratory diagnostic unless the file is statistical | Statistical result or exploratory diagnostic |
| Typological reading | Theological or literary interpretation | Preserved if textually anchored, but claim-status controlled |

Do not treat inverse material as having the same system-level status as the Mirror unless the file explicitly narrows itself to inverse-number mechanics.

Correct:

`The Mirror result completes the cross-axis coordinate identity of the Luke/Jared node and is therefore classified as Mirror coordinate-completion. The inverse landing is retained as appendix-only because File_54 is not an inverse-focused file.`

Incorrect:

`Mirror and inverse material are both secondary appendix-only observations.`

---

## 19. Naming Specific States

### 19.1 First-use full descriptor

On first use within a section, give the full descriptor when ambiguity is possible.

Examples:

- `Scaffold +60 base anchor: 4166 BC`;
- `MT Year-6 anchor: 4116 BC`;
- `Upper rounded MT +60 Creation boundary: 4171 BC`;
- `Mirror target of the MT Year-6 anchor: AD 4115`;
- `Transmitted SP lower rounded boundary: 4411 BC`.

### 19.2 Short reuse

After the full descriptor has appeared within the same section, a shortened form may be used if ambiguity is low.

### 19.3 Across sections

Do not assume a short form remains clear across section boundaries. Restate the full descriptor when entering a new dense section.

### 19.4 Specificity hierarchy

When naming a state, prefer specificity in this order:

1. chronological tradition;
2. state-type;
3. variant or overlay;
4. node-class;
5. date.

Example:

```markdown
MT rounded +30 Apparent Age Creation anchor: 4136 BC
```

---

## 20. State-Status Terms

### 20.1 Preferred terms

Use these carefully and consistently:

- `transmitted state`;
- `alternate state`;
- `working state`;
- `comparison state`;
- `modal state`;
- `local comparison state`;
- `display label`;
- `computational state`;
- `secondary overlay`;
- `appendix-only state`.

### 20.2 Use

If one state is adopted for the current file while another is acknowledged but not used, say so explicitly.

Example pattern:

- `transmitted SP state` = working state in this file;
- `alternate local option` = noted but not adopted.

### 20.3 Do not collapse states

Avoid editorial revisions that turn distinct states into vague alternatives.

Incorrect:

```markdown
The date may be 4416 or 4411 BC.
```

Correct:

```markdown
The transmitted SP rounded Creation block is 4416/4411 BC. The pair functions as an ordered block, not as an ordinary uncertainty range.
```

---

## 21. Prose Style

### 21.1 Default form

Default to prose paragraphs.

### 21.2 Use lists sparingly

Lists are appropriate for:

- genuine series of 3 or more items;
- summary sections;
- compact procedural sequences;
- audit checklists;
- table-framing aids.

Do not overuse lists for material that is better expressed as direct prose.

### 21.3 Human-readable but AI-forward

Source files should remain readable to humans, but their primary obligation is structural clarity for AI and future revision.

That means:

- short logical units;
- explicit state-tags;
- explicit sign conventions;
- minimal prose drift;
- no fluff;
- no hidden operator changes;
- no unexplained modal transitions.

### 21.4 Paragraph control

Dense paragraphs should be decompressed when they contain multiple state shifts, operator shifts, or claim-status shifts. Decompression should clarify the logic without diluting technical precision.

---

## 22. Appendix Policy

### 22.1 Function of appendices

Appendix material should be used for:

- secondary corroboration;
- providential overpattern;
- Mirror stress-tests;
- statistical scans;
- weak but useful observations;
- technical derivations that would interrupt the main argument;
- exploratory calculations not yet promoted into the main thesis.

### 22.2 Primary claim rule

Appendix material must not carry the primary claim unless explicitly promoted into the main body.

### 22.3 Appendix-only label

When material is useful but not load-bearing, label it as appendix-only.

Example:

```markdown
Claim-status note:
This observation is appendix-only. It may clarify the larger pattern but does not carry the main argument.
```

### 22.4 Weak observation rule

Weak observations may be retained as footnotes or appendix notes if they clarify a stronger point. They should not expand the main argument.

### 22.5 Providential pattern rule

Providential synchronization may be recorded when arithmetic is exact and the symbolic relation is coherent. It must be labeled separately from authorial intent.

---

## 23. Publication-Layer Notes

### 23.1 Markdown does not enforce editorial correctness

Markdown handles structure. It does not itself enforce:

- capitalization;
- no commas in numbers;
- hyphenation policy;
- terminology discipline;
- modal-state consistency;
- claim-status discipline;
- arithmetic correctness.

Those are repository style rules and must be maintained editorially.

### 23.2 WordPress conversion

When converting to WordPress:

- preserve section numbers;
- preserve heading hierarchy;
- preserve table structure where possible;
- preserve math notation;
- preserve no-comma number formatting;
- preserve BC/AD formatting;
- do not let WordPress become the editing source again.

### 23.3 PDF and DOCX conversion

PDF and DOCX outputs are derived publication forms. They may improve visual presentation, but they must not become the source of future textual revision unless converted back into Markdown and audited.

---

## 24. File Intake Sheet

### 24.1 Required intake sheet for revision projects

Before revising a file, create a compact intake sheet.

Recommended form:

```markdown
# File Intake Sheet

File:
Current title:
Current source format:
Current status:
Primary topic:
Primary anchors:
Major traditions involved:
Major ratios/operators:
Dependencies:
Known unresolved issues:
Revision priority:
Risk level:
```

### 24.2 Function

The intake sheet prevents the revision process from beginning with prose smoothing before the file’s state, dependencies, and risks are understood.

### 24.3 Intake rule

For high-risk or critical files, complete the intake sheet before rewriting any prose.

---

## 25. Risk Rating

### 25.1 Required risk rating

Assign a risk rating before editing.

| Risk | Description | Handling |
|---|---|---|
| Low | Mostly formatting and terminology | Revise directly |
| Medium | Some modal states or arithmetic need clarification | Revise with audit notes |
| High | Dense arithmetic, Mirror logic, Prime dependencies, or unresolved constants | Create annotated draft before final rewrite |
| Critical | Depends on missing Prime Files or undefined operators | Do not infer; mark dependency |

### 25.2 Dependency-blocked files

If a file depends on missing operators, undefined Prime constants, or unavailable prerequisite files, do not invent the missing structure.

Use:

```markdown
Audit note:
This section depends on [missing file/operator/constant]. Do not infer. Mark as dependency blocked until the prerequisite is supplied.
```

### 25.3 High-risk workflow

For high-risk files, use a two-step revision process:

1. produce audit and revision plan;
2. revise after the audit is accepted or clarified.

---

## 26. The Do-Not-Break-the-Repository Rule

When revising, never silently change:

- an anchor date;
- a span;
- a modal state;
- a node-class;
- a sign convention;
- an operator;
- a mirror protocol;
- a Cainan / +60 / +215 / +30 state;
- a rounded vs actual distinction;
- a regular vs cumulative distinction;
- a transmitted vs alternate state;
- a display label vs computational state;
- a primary argument into an appendix-only claim, or the reverse.

If a file contains an apparent error, mark it as:

```markdown
Audit note:
This value appears inconsistent with [specific rule/calculation]. Do not revise silently. Requires author decision.
```

Precision outranks smoothness. Repository continuity outranks local elegance.

---

## 27. Per-File Revision Workflow

Every file goes through the same consolidated workflow (Project Procedures v3.0).

### 27.1 Pass 0 — Intake + Mechanical Lint

Create or update the File Intake Sheet (§24). Assign risk level: Low, Medium, High, or Critical (§25). Run the mechanical lint and attach its report. Produce the section-level revision plan, early audit notes, and controlling exemplar(s). No revision occurs in Pass 0.

### 27.2 Pass 1 — Unified Revision Pass

One controlled rewrite applying the five editorial layers of §2A simultaneously: Structural, Terminology, Modal-State, Arithmetic, Argument. All content invariants apply (Machine Guard [UNIFIED PASS INVARIANTS]).

Deliverables: revised Markdown; audit notes; unresolved issues; recommended cross-file updates; Revision Log.

High-risk split: for High or Critical risk ratings, Pass 1 divides once — Structural + Terminology + Modal-State first, then Arithmetic + Argument.

### 27.3 Pass 2 — Verification Pass

1. Machine diff between source file and revised file.
2. Audit of the diff by change class: every change must be formatting, terminology, or an explicitly logged correction; nothing outside those classes may have changed.
3. Scripted arithmetic recheck where spans and products are parseable; mismatches become `Audit note:` candidates, never silent corrections.
4. Consolidated Author-Decision list: every reserved item presented once, recommendation first.

### 27.4 Finalization

Only when the author says to mark the file Final. Same content as the former Finalization Pass: set `Status: Final`; remove temporary pass-language; retain necessary audit and dependency notes; update the Revision Log; list unresolved issues and required cross-file updates; verify the File map; verify no derived-AI-format reshaping. Then offer a pressure test.

### 27.5 Publication Pass

Prepare derived publication format only after Markdown is stable (§2A.6).

### 27.6 Revision Log

After revision, record:

```markdown
Revision Log:
- date
- passes completed
- unresolved issues
- author decisions needed
- cross-file updates required
```

### 27.7 Vocabulary registration

When a file is finalized, register its new state vocabulary, convention updates, and Machine Guards in the State Vocabulary Register, and append the Update Record to the Repository_Change_Archive. The Style Guide and Project Procedures receive at most a one-line status pointer; they no longer absorb per-file vocabulary.

---

## 28. Repository Review Order

Do not revise files in numerical order only. Review them in dependency order.

### 28.1 Recommended dependency order

| Phase | Files | Reason |
|---|---|---|
| Phase 1 | Style Guide + Restart Capsule | Controls all later revisions |
| Phase 2 | File 51a, 51b, 51c, 52a–52e, 53 | Current standard-bearing files |
| Phase 3 | Files 0–10 | Foundational biblical chronology |
| Phase 4 | Files 11–28 | Regular / cumulative / manuscript-tradition expansion |
| Phase 5 | Files 29–41 | Prime system, only after dependencies are clearly defined |
| Phase 6 | Files 42–50 | High-complexity bridge files |
| Phase 7 | Cross-file index, glossary, master anchor table | Final harmonization |

### 28.2 Pilot set

Start with a small pilot batch before revising everything.

Recommended pilot:

| File | Why |
|---|---|
| Style Guide | Must be hardened first |
| File_51a | Main template source |
| File_51b | Mirror and deep-time standard |
| File_51c | BJ macro-rounded witness |
| File_52a | Inverse architecture standard |
| File_53 | Tests authorial/providential classification |

### 28.3 Second batch

After the pilot:

| File group | Focus |
|---|---|
| Restart Capsule | Ensure all later files cite the same constants |
| Files 52a–52e | Inverse architecture and modal-state discipline |
| Files 47–50 | Prime and high-dependency material |
| Files 0–30 | Backfill older material |

### 28.4 Reason for dependency order

The newer files already embody the current standard and should become stable exemplars before older files are rewritten.

---

## 29. Repository-Wide Control Files

### 29.1 File Inventory Table

Create a master table:

| File | Title | Status | Domain | Primary anchors | Dependencies | Risk | Revision status |
|---|---|---|---|---|---|---|---|

### 29.2 Master Anchor Table

Create one cross-file table for repeated anchors:

| Anchor | Date | Node-class | Active files | Modal notes |
|---|---:|---|---|---|

Examples of anchors to include:

- `1406 BC`;
- `1446 BC`;
- `1399 BC`;
- `4106 BC`;
- `4116 BC`;
- `14006 BC`;
- `6 BC`;
- `AD 1405`;
- `AD 29515`.

### 29.3 Modal-State Glossary

Create a controlled glossary for:

- actual;
- rounded;
- regular;
- cumulative;
- transmitted state;
- alternate state;
- endpoint;
- anchor;
- boundary;
- block;
- envelope;
- mirror target;
- apparent-age overlay;
- restored 2nd Cainan;
- Cainan expunged;
- Protocol 1;
- Protocol 2;
- Priestly 336-day Ledger state;
- 24-course roster source-control state;
- seven-day service-period state;
- Sabbath transition-boundary state;
- Priestly-Enochian bridge corollary;
- Priestly-Enochian half-week straddle;
- source-control bibliography vector;
- Christological joint-file state;
- Second-Adam / Jan-1 covenant numeric-year Mirror;
- phase-resolved paired Mirror coordinate-completion;
- File_13 Passion-date pair state;
- File_13 day-year purification display;
- Matthew exile-bearing Abraham head bracket;
- cumulative MT Shem / Noah Mirror state;
- LXX actual Creation endpoint state;
- LXX actual Year-6 state;
- AD 33n / AD 30n / AD 33t / AD 34 display-state firewall.
- Rod of Enoch state.
- Pi master-formula state.
- Pi convergent generator state.
- AD 33 solar synchronization state.
- Samaria Node schematic envelope state.
- actual Fall of Samaria state.
- Israel literal-reign schematic ledger.
- Samaria / Jerusalem twin-city judgment vector state.
- Samaria Node / Immanuel 720 overlay state.
- Samaria Node three-tradition Creation overlay state.
- Abrahamic 240-cycle overlay state.
- Samaria Node sub-year marker exploratory note.


File_18 adds the following glossary candidates to the controlled state-register layer:

- raw data source state;
- minimum baseline table state;
- source-table state;
- shared year-label state;
- envelope member-label;
- phase-resolved envelope member;
- website-to-minimum adjustment state;
- SP Shem Superposition;
- Abraham / Terah four-position field;
- 2nd Cainan variant-boundary state;
- Pentateuchal Funnel / all-even structural harmony state;
- Cainan macro-vector B6 state;
- audit-controlled `2307` / solar companion state;
- File_18 LXX corrected source-table state;
- MT cumulative Peleg phase-resolved Mirror application;
- SKL display-state rail dependency;
- File_18 / File_21 Etana SKL opening-anchor state.


File_34 adds the following glossary candidates to the controlled SKL / Berossus state-register layer:

- File_34 post-final citation-control state;
- Berossus computational-anchor state;
- fall-of-Babylon / restoration / Berossus-anchor three-state field;
- Precessional Envelope state;
- Cosmic Pixel state;
- SKL base / rail firewall;
- SKL-to-Berossus `2370` corridor state;
- `30 + 20 + 30` restoration corridor;
- paired slash-display arithmetic;
- Nisan / Tishri phase-chain arithmetic;
- Appendix B phase-chain dependency state;
- Pillar / AD target state;
- Sanctuary Fractal / Key-of-23 expansion state;
- authorial forward-time plus display;
- expansion difference / non-Residue state;
- state-conditioned SKL `+1260` display.

### 29.4 Cross-File Dependency Register

For every file, record:

| File | Depends on | Operator dependency | Safe to revise? |
|---|---|---|---|

This is especially important for Prime Files 29–41.

---

## 30. Practical AI Revision Prompt

Use this prompt template for each file revision:

```text
You are revising File_[number] under 490d Repository Style Guide v2.5, Project Procedures v3.0, the Restart Capsule, and the State Vocabulary Register entries active for this file.

Pass 0 (this turn): produce only the File Intake Sheet, risk rating, lint report, revision plan, early audit notes, and controlling exemplar(s). Do not revise.

Pass 1 (next turn): one Unified Revision Pass applying the Structural, Terminology, Modal-State, Arithmetic, and Argument layers simultaneously.
1. Preserve all arithmetic, anchors, modal states, node-classes, sign conventions, operators, Mirror protocols, and theological claims unless a clear inconsistency is identified.
2. Normalize Markdown structure, headings, terminology, number formatting, BC/AD format, table framing, and math notation.
3. Identify but do not silently fix uncertain arithmetic; use Audit note: / Dependency note:.
4. Label claim-status where needed.
5. Return: revised file text; audit notes; unresolved issues; recommended cross-file updates; Revision Log.

Pass 2 (final turn): Verification Pass — machine diff against the source, change-class audit, arithmetic recheck, consolidated Author-Decision list.

End every response with a Next Step statement.
```

For High or Critical risk files, split Pass 1: layers 1–3 in one turn, layers 4–5 in the next.

---

## 31. Modal-State Glossary: Working Definitions

Generic, repository-wide states are defined here (§31.1–§31.37). All file-specific entries — former §31.38–§31.167 — were migrated verbatim, numbering preserved, to the State Vocabulary Register v1.0. Read any cross-reference to `Style Guide §31.38`–`§31.167` as `State Vocabulary Register §31.38`–`§31.167`.

### 31.1 Actual

An unrounded chronological state, usually referring to the textual or computed chronology before rounded scaffold adjustment.

### 31.2 Rounded

A scaffolded or rounded chronological state used for structural comparison, mod-5 analysis, or larger repository architecture. A rounded state is not automatically a literal chronology. When the term refers to the Rounded Scaffold, it belongs to the methodological mod-5 comparison layer unless the active file explicitly promotes it into its own argument.

### 31.3 Regular

The standard patriarchal or biblical chronological line as distinct from the cumulative chronology.

### 31.4 Cumulative

A chronology produced by accumulating lifespans or spans end-to-end rather than using ordinary begetting chronology.

### 31.5 Transmitted state

The state preserved in the textual or traditional form being used as the working datum.

### 31.6 Alternate state

A recognized variant or local option that is acknowledged but not necessarily adopted as the working state.

### 31.7 Endpoint

A terminal date or boundary in a span, block, envelope, or structural sequence.

### 31.8 Anchor

A date that governs or stabilizes a calculation, file, system, or structural comparison.

### 31.9 Boundary

A date functioning as the edge of a block, envelope, phase, or chronological range.

### 31.10 Block

A structured pair or set of dates treated as a coherent unit.

### 31.11 Envelope

A range or spread that contains phase-resolved or multiple valid internal states.

### 31.12 Mirror target

The corresponding date or state produced by a Mirror protocol.

### 31.13 Apparent-age overlay

A secondary overlay, especially the +30 Apparent Age of Adam, applied only where the file explicitly defines it as active.

### 31.14 Restored 2nd Cainan

A chronological state in which the 2nd Cainan is retained or restored as a valid component.

### 31.15 Cainan expunged

A chronological state in which the 2nd Cainan is omitted or removed from the active computation.

### 31.16 Protocol 1

Pure rounded A-space integer mirror.

### 31.17 Protocol 2

Tishri/Nisan phase mirror, midpoint-pivot.

### 31.18 Nisan-state label

A calendar-state display label marked by suffix `n`. It identifies a Nisan / spring state where the local file uses suffixed dates. It is not automatically a `.5` computational state.

### 31.19 Tishri-state label

A calendar-state display label marked by suffix `t`. It identifies a Tishri / fall state where the local file uses suffixed dates. It is not automatically a `.5` computational state.

### 31.20 Physical residue

Actual day-drift against the Residue Protocol calibrated solar year `S_K`, computed as `N / 40 days` when the Residue Protocol is explicitly active.

### 31.21 Conceptual residual-display

A liturgical or day-year display value generated by passing physical residue through the same Key-of-23 ratio that governs the corresponding year conversion. It is not physical drift and must not be fed back into ordinary date arithmetic.

### 31.22 Residual day-year lift

The conceptual operation by which residue-days echo residue-years. Example: `6.9 years × 70/69 = 7 years`; therefore `6.9 physical residue-days` may display as `7.0 residual-display days` under the day-year analogy.

### 31.23 MT Minimum-Regular

The forward-most regular MT comparison state. In `File_02`, the MT Minimum-Regular Flood is `2243 BC`.

### 31.24 MT Standard-Normal

The normative operating MT state under the full 430 years in Egypt and without `+60 Terah`. In `File_02`, the MT Standard-Normal Flood is `2458 BC`.

### 31.25 Cumulative Flood Week

A cumulative week-of-years envelope. In `File_02`, the base rounded cumulative Flood Week is `4836–4829 BC`, and the restored cumulative 2nd Cainan Flood Week is `5296–5289 BC`.

### 31.26 Judgment-week envelope

The AD-side envelope paired with a cumulative Flood Week by civil cross-axis arithmetic. In `File_02`, the judgment-week envelope is `AD 65–72`, with AD 70 as the primary internal event-target.

### 31.27 Sumerian A / SKL Short

The SKL state in which the 23 kings have the whole-year total `17980`. The Physical state begins at `20886 BC` and is anchored to `2906 BC`.

### 31.28 Sumerian B / SKL Long

The SKL state in which the 23 kings have the whole-year total `24510`. The Physical state begins at `27366 BC` and is anchored to `2856 BC`.

### 31.29 SKL +30 Apparent Mode

A global SKL mode rail shifting the SKL beginning-and-anchor pair by 30 years while preserving the whole-year total.

### 31.30 SKL +2 local rail

A local two-year SKL rail shifting the beginning-and-anchor pair by two years while preserving the whole-year total. It is related to the `+720 scale-state` but must not be substituted for it without an explicit scale shift.

### 31.31 SKL +720 scale-state

The cosmic SKL/Berossus expression related to the `+2 local rail` through `2 years = 720 days`. It appears as a `+720` or `±720` year rail only when the file explicitly shifts into SKL/Berossus cosmic scaling.

### 31.32 Whole-year total

The integer SKL total used for local arithmetic when an appended month/day textual datum is preserved but dependency-controlled. In `File_02`, the whole-year totals are `17980` and `24510`.

### 31.33 Appended month/day textual datum

The SKL phrase `3 months and 3.5 days`, preserved in addition to the whole-year total. Its full function remains dependency-controlled by `File_34` unless a file explicitly opens that operator.

### 31.34 File map

A terse functional index near the top of a repository file. It identifies where major logic, states, operators, or dependency controls are located. It is not a decorative table of contents.

### 31.35 Rounded Scaffold forward reference

A clarity-only reference to a Rounded Scaffold value before the Rounded Scaffold is directly opened by `File_51a` or a later rounded-focused file. Its purpose is to prevent state confusion, not to make the rounded value a literal chronology.

### 31.36 State-safe retrieval

A retrieval condition in which a section, paragraph, table, File map entry, Machine Guard, or appendix note is retrieved together with enough local context to identify the active state, node-class, operator, chronological tradition, claim-status, and dependency status.

### 31.37 Derived AI format

Any AI-facing format generated from the canonical Markdown source, including RAG index records, embedding metadata, Knowledge Graph records, JSON exports, JSONL training pairs, or prompt/response datasets. Derived AI formats must preserve source meaning and must not become the canonical source.

### 31.38–31.167 Per-file states (migrated)

Migrated verbatim to State_Vocabulary_Register v1.0, Part A, numbering preserved. The Register entries are active controls of equal authority. New per-file states register there, not here.

---

## 32. File 51-Derived Standard Summary

The strongest standards derived from File 51 are these:

1. no commas in numbers or dates;
2. preserve modal states rather than collapsing them;
3. define sign conventions locally;
4. distinguish node-classes explicitly;
5. preserve exact half-year states internally;
6. separate mirror-generation protocol from cross-axis span operator;
7. distinguish same-side subtraction from cross-axis arithmetic;
8. use restrained Markdown as the canonical source;
9. keep prose exact, spare, and non-inflated;
10. frame dense tables before presenting them;
11. restate state-tags when a dense paragraph changes system or node-class;
12. do not silently repair values that require author decision.

---

## 33. Final Governing Principle

The revision program must not make the repository smoother at the expense of precision. It must make every file more explicit about its active state, node-class, arithmetic operator, claim-status, and dependency structure.

The desired result is a Markdown-first corpus that human readers can follow and advanced AI systems can parse, retrieve, and transform without collapsing modal states, inventing missing dependencies, confusing publication formatting with source authority, or treating derived AI formats as canonical source.

The governing rule is therefore:

**clarify the logic, preserve the terminology, reduce compression, add no ornament.**

And the governing safeguard is:

**do not silently change the repository’s arithmetic, anchors, modal states, node-classes, operators, sign conventions, or mirror protocols. If a value appears wrong, mark it for audit rather than correcting it without review.**

---

## 34. Revision Log: v2.5

| Item | Status |
|---|---|
| Version number | Advanced from v2.4 to v2.5 |
| Revision date | June 10 2026 |
| Authorizing decisions | Repository Revision Plan v3.0 §9, Decisions 1–3, author-approved June 10 2026 |
| Workflow change | §2A and §27 rewritten: six sequential passes replaced by Pass 0 (Intake + Lint), Pass 1 (Unified Revision Pass, five editorial layers), Pass 2 (Verification Pass with machine diff); High-risk split retained; Publication Pass retained; Finalization unchanged as author-invoked |
| Prompt template | §30 updated to the three-turn form |
| Vocabulary migration | §31.38–§31.167, §32A–§32U, and File_36 / File_41 / File_45 glossary additions and Machine Guards migrated verbatim to State_Vocabulary_Register v1.0; original numbering preserved; pointer sections added |
| History migration | All Cross-File / Style-Guide Update Records and the v2.4 Revision Log Addendum migrated verbatim to Repository_Change_Archive v1.0 (non-controlling) |
| Content invariants | No arithmetic, anchor, modal state, node-class, sign convention, operator, slash-pair, range, envelope, Mirror protocol, claim-status label, Machine Guard content, theological claim, or dependency boundary altered; verified by line-accounting and block-verbatim diff audit June 10 2026 |
| Rules retained unchanged | §0–§1C, §2–§2B (except §2A workflow form), §3–§26, §28–§29, §31.1–§31.37, §32, §33 |
| Pressure-test status | Diff-audited at migration; full pressure test available on author request |
