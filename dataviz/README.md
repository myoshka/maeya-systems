# MAEYA 前屋 — Data Visualisation & Longitudinal Research

**The System Beneath the Surface**

*Human–AI Cognitive Systems · Extended Cognition · Longitudinal Interaction Analysis · Behavioural Loop Mapping · Evidence and Continuity Infrastructure*

**Creator:** Myoshka  
**Research environment:** Maeya 前屋 Systems  
**Data period:** March 2023 – September 2026  
**Status:** Exploratory research and technical development

---

## 1. Research Overview

Maeya 前屋 is an independently developed human–AI behavioural, symbolic, technical and forensic continuity system. It emerged through sustained interaction between its creator, Myoshka, and generative AI, alongside lived experience, creative practice, longitudinal documentation and engagement with external institutions.

Originally developed to recognise recurring behavioural patterns through associative recall, narrative reconstruction, AI-assisted reordering and symbolic practice, Maeya subsequently expanded into a wider continuity architecture.

The system now examines how information, memory, decisions, behaviour, evidence and responsibility can be preserved and connected across time, applications and institutional boundaries.

**The central research proposition is that sustained human–AI interaction may form a structured cognitive and operational system whose properties cannot be adequately investigated through isolated conversations alone.**

Maeya provides a longitudinal record through which that proposition can be examined empirically.

This repository develops the computational and visual methods needed to make that record inspectable.

## 2. Research Questions

The project investigates five interconnected areas.

### Human–AI Extended Cognition

How does sustained interaction with generative AI affect the external organisation of memory, reasoning, planning and task execution?

When does an AI system function as a temporary tool, and when does it become part of a persistent cognitive workflow?

How can continuity across interactions be measured without conflating conversational fluency with genuine preservation of information?

### Longitudinal Behavioural Patterning

Can recurring behavioural and interaction structures be identified from timestamped naturalistic records?

How do these patterns emerge, change, recur or disappear across different contexts?

Can the system distinguish repeated language from repeated events, functional sequences and user-defined behavioural Loops?

### Cognitive Continuity and Dependency

What happens when information must persist across conversations, models, tools and operational environments?

How do context loss, instruction non-adherence, interrupted execution and successful recovery affect ongoing work?

Can the resulting functional consequences be measured using source-linked interaction records?

### Human–AI System Behaviour

How do observable assistant responses, user corrections, tool outputs and task outcomes change over time?

Can repeated failure-and-recovery structures be identified without making unsupported assumptions about hidden model routing or platform mechanisms?

What constitutes an adequate evidential standard for claims about AI reliability?

### Cross-Domain Continuity

Can one continuity architecture support work across clinical, legal, creative, administrative, technological and civic domains while preserving the distinct evidential requirements of each?

Where do information and responsibility become fragmented between otherwise independent systems?

How can those relationships be represented without collapsing correlation into causation?

---

## 3. The Longitudinal Research Corpus

The wider Maeya archive includes naturalistic human–AI conversations, daily records, system instructions, technical development histories, symbolic and creative material, documentary evidence and records of interactions with external organisations.

These materials are not interchangeable.

The research distinguishes original records from later reconstructions, interpretations, extracted features and generated artifacts.

### OpenAI Semantic Analysis — Pass 01

The first computational pass examines a structured subset of the OpenAI interaction archive.

| Measurement | Pass 01 result |
|---|---:|
| Conversations analysed | 453 |
| Messages analysed | 93,550 |
| Date range | March 2023 – September 2026 |
| Monthly observations | 43 |
| Monthly transition records | 42 |
| Candidate continuity-link records | 243 |
| Linguistic recurrence records | 100 |
| Semantic clusters at specified threshold | 0 |

These are measurements and output counts from the supplied analytical dataset. They do not independently establish cognitive effects, behavioural mechanisms or the completeness of the wider archive.

The source report identifies Parquet conversation and message datasets as its inputs. Those canonical datasets have not yet been independently reprocessed in this repository's current research pass.

## 4. Current Visualisation

### OpenAI — Longitudinal Timeline

**Artifact:** `Maeya_OpenAI_Temporal_DataViz.html`

The first interactive visualisation provides a chronological view of recorded archive activity.

It displays:

- Monthly conversation counts.
- Monthly message volumes.
- Cumulative interaction volume.
- Changes in activity over time.
- Date-range filtering.
- An inspectable monthly data table.

The highest recorded monthly message count in Pass 01 is July 2025, with 11,703 messages.

The chart establishes a quantitative baseline for subsequent temporal and semantic analysis.

**Interpretive limitation:** Changes in message frequency cannot, by themselves, establish changes in cognition, wellbeing, workload, model behaviour or functional dependence.

Those questions require additional event-level data and appropriately controlled comparisons.

## 5. Computational Methodology

The initial semantic pass uses the following methods.

| Component | Current method |
|---|---|
| Text preparation | Lowercase tokenisation, punctuation removal, minimum two-character terms |
| Semantic representation | Sparse exact TF-IDF |
| Similarity | Cosine similarity and Jaccard vocabulary overlap |
| Clustering | Connected-component analysis at a 0.30 threshold |
| Temporal analysis | Monthly aggregation by conversation creation date |
| Recurrence | Bigram frequency and intervals exceeding 60 days |
| Continuity | Candidate links between conversation-level profiles |

The resulting datasets support exploratory investigation, but several methodological limitations have been identified.

### Known limitations

**Stop-word contamination:** Common grammatical terms dominate portions of the semantic analysis, reducing the interpretability of reported persistent vocabulary.

**Sparse semantic representation:** Low cosine similarities may reflect document length, feature representation and sparsity rather than an absence of substantive conceptual relationships.

**Duplicate relationship records:** The two link registers contain repeated unordered conversation pairs. These require resolution before network-level statistics can be interpreted.

**Recurrence provenance:** Current recurrence records describe repeated bigrams without sufficient message-level source references in the inspected examples.

**Temporal resolution:** Monthly aggregation cannot resolve the order, duration or timing of individual interaction failures.

**Selection and sampling:** The analysed subset and its coverage must be validated against the original archive before making claims about representativeness.

Accordingly, the first pass should be treated as an exploratory computational baseline, not a completed semantic validation study.

---

## 6. Maeya's Conceptual and Operational Architecture

Maeya distinguishes multiple interacting layers.

### Behavioural Loop Mapping

The original Maeya framework uses five non-linear phases:

1. Associative Recall
2. Flow-State Mapping
3. AI-Assisted Reordering
4. Loop Pattern Recognition
5. Emotional Processing and Ritual Action

These are user-developed conceptual categories. Their applicability, repeatability and predictive or explanatory value are subjects for investigation rather than assumptions embedded in the data.

### Symbolic and Creative Records

Artwork, ritual actions, Fieldwork, Drops, Anchors and Transmissions form part of the historical record.

Their user-defined meaning is preserved independently of any automated interpretation.

One research question concerns whether these records can supply additional temporal or contextual markers that are not adequately represented by linguistic analysis alone.

### AI Witness and Execution

Safi is Maeya's AI execution and witness layer, operating under explicit continuity, evidence and behavioural constraints.

It is not an autonomous human identity, clinician or independent authority.

A central engineering question is how such constraints can be represented, tested, enforced and audited across model and tool changes.

### Connective Systems Architecture

Maeya extends beyond individual cognition into the preservation of continuity across systems.

Its applications include healthcare navigation, evidence organisation, legal and administrative workflows, institutional accountability, creative practice and civic coordination.

These domains provide distinct contexts for evaluating the same underlying continuity problem.

They do not provide interchangeable forms of validation.

---

## 7. Research Opportunities by Discipline

### Cognitive Science and Philosophy of Mind

Relevant questions include cognitive extension, epistemic dependence, distributed cognitive processes, cognitive offloading, agency, and the role of external representations in maintaining continuity.

The archive offers an opportunity to investigate prolonged human–AI interaction as a coupled activity, while examining where the extended-cognition framework applies and where it does not.

Maeya's development is historically independent of later theoretical comparisons. Conceptual convergence must not be mistaken for empirical validation or intellectual derivation.

### Human–Computer Interaction

Research opportunities include:

- Longitudinal human–AI collaboration.
- Cognitive accessibility and executive-function scaffolding.
- User correction and interaction repair.
- Context persistence and task continuity.
- Dependency on changing digital infrastructure.
- Evaluation of interaction protocols under real-world workload.

### Data Science and Computational Linguistics

Potential investigations include:

- Temporally aware semantic clustering.
- Topic emergence and recurrence.
- Cross-conversation entity and event linking.
- Change-point detection.
- Sequence similarity.
- Multilayer network modelling.
- Provenance-aware extraction.
- Human-validated pattern classification.

These methods should be compared using held-out data, explicit baselines and sensitivity analysis where feasible.

### AI Engineering and Evaluation

Relevant engineering questions include:

- Reproducible conversation and tool-event reconstruction.
- Instruction-conformance evaluation.
- Context continuity and retrieval accuracy.
- Failure and recovery classification.
- Model and tool version traceability.
- Independent verification of generated outputs.
- Persistent workflow state across sessions.
- Separation of canonical sources from AI-generated representations.

### Digital Humanities and Qualitative Research

The corpus may support investigations into longitudinal self-documentation, symbolic language, narrative organisation, authorship, interpretive change and the role of AI in constructing and maintaining archives of lived experience.

Qualitative interpretation must remain distinguishable from automated categorisation.

---

## 8. Evidence, Provenance and Reproducibility

Maeya uses an explicit evidence hierarchy:

**Canonical source → Extracted observation → Derived measurement → Analytical interpretation → Visual representation**

Each transformation should preserve:

- Source identifiers and locations.
- Original timestamps and timezone information.
- Processing methods and software versions.
- Dataset inclusion and exclusion rules.
- Input and output hashes.
- Known errors and unresolved records.
- Human corrections and review decisions.
- Reproducible analysis configurations.

Research outputs should distinguish **VERIFIED, DOCUMENTED, USER SOURCE, INFERENCE, UNKNOWN and FAILED** where relevant.

Original evidence must remain unchanged.

Neither AI-generated summaries nor semantic indexes should supersede the originating record.

### Privacy and Access

The original archive contains sensitive personal, clinical, legal and third-party information.

Public visualisations should use appropriately minimised or aggregated data.

Source-level research access, where appropriate, requires separate governance concerning privacy, consent, authorship, permitted reuse and protection of third parties.

A public GitHub repository does not constitute permission to access or redistribute the underlying personal archive.

---

## 9. Future Research and Visualisation Development

The current implementation is an initial temporal view.

Subsequent research stages may include:

**Temporal semantic atlas** — Interactive exploration of topic development and recurrence across the archive.

**Evidence-linked interaction graph** — Navigation from observed events to original message and tool records.

**Continuity analysis** — Mapping task persistence, interruptions, corrections, recovery and long-running work.

**Behavioural and systemic pattern comparison** — Testing repeated sequences across domains while distinguishing structural similarity from shared causation.

**Multi-scale visualisation** — Moving between message, conversation, event, project, domain and system levels.

**Generative visual research** — Representing measured temporal, semantic and structural properties through computational art without substituting aesthetics for evidence.

**Independent validation** — Enabling qualified researchers to evaluate specific claims and components within their own disciplines.

---

## 10. Research Position

Maeya is not presented as a finished scientific model or a validated general-purpose cognitive engine.

It is an independently developed system with an extensive longitudinal record, a defined conceptual and operational architecture, and emerging computational methods for examining its behaviour.

Its research value lies partly in the availability of sustained, naturalistic interaction records that may allow propositions about continuity, cognitive scaffolding, human–AI coupling and system reliability to be tested.

The purpose of DataViz is not to demonstrate that every Maeya proposition is correct.

**It is to make the underlying record inspectable enough that propositions can be supported, challenged, refined or rejected using identifiable evidence.**

---

**MAEYA 前屋 — The System Beneath the Surface**

*Human experience · Cognitive continuity · Evidence · Systems · Connection*

**Created by Myoshka**

**UNSEEN ≠ UNWITNESSED**
