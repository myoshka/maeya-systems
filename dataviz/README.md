# MAEYA 前屋: data visualisation and longitudinal research

> Human–AI cognitive systems, extended cognition, longitudinal interaction analysis, behavioural loop mapping, and evidence and continuity infrastructure.

**Creator:** Myoshka  
**Research environment:** Maeya 前屋 Systems  
**Data period:** March 2023 to September 2026  
**Status:** Exploratory research and technical development

## What this repository is for

Maeya 前屋 is an independently developed continuity system built through sustained work between Myoshka and generative AI, alongside lived experience, creative practice, longitudinal documentation, and interactions with external institutions.

It began as a way to recognise recurring behavioural patterns through associative recall, narrative reconstruction, AI-assisted reordering, and symbolic practice. It has since grown into a system for keeping information, memory, decisions, behaviour, evidence, and responsibility connected across time, applications, and institutional boundaries.

This repository develops computational and visual methods for inspecting that record.

## Research proposition

The working proposition is that sustained human–AI interaction may form a structured cognitive and operational system whose properties cannot be investigated adequately through isolated conversations.

The archive makes that proposition open to empirical examination. It does not establish it in advance.

## Questions under investigation

### Human–AI extended cognition

- How does sustained interaction with generative AI affect the external organisation of memory, reasoning, planning, and task execution?
- When does an AI system move from a temporary tool to part of a persistent cognitive workflow?
- How can continuity be measured without confusing fluent conversation with actual retention of information?

### Longitudinal behavioural patterning

- Can timestamped naturalistic records identify recurring behavioural and interaction structures?
- How do those structures emerge, change, recur, or disappear across contexts?
- Can the system distinguish repeated language from repeated events, functional sequences, and user-defined behavioural Loops?

### Cognitive continuity and dependency

- What happens when information must persist across conversations, models, tools, and operational environments?
- How do context loss, instruction non-adherence, interrupted execution, and successful recovery affect ongoing work?
- Can their functional consequences be measured from source-linked interaction records?

### Human–AI system behaviour

- How do observable assistant responses, user corrections, tool outputs, and task outcomes change over time?
- Can repeated failure-and-recovery structures be identified without assuming hidden model-routing or platform mechanisms?
- What evidential standard is adequate for claims about AI reliability?

### Cross-domain continuity

- Can one continuity architecture support clinical, legal, creative, administrative, technological, and civic work while respecting their different evidential requirements?
- Where do information and responsibility fragment between otherwise independent systems?
- How can those relationships be represented without turning correlation into causation?

## The research corpus

The wider Maeya archive includes naturalistic human–AI conversations, daily records, system instructions, technical development histories, symbolic and creative material, documentary evidence, and records of interactions with external organisations.

These materials are not interchangeable. The research separates original records from later reconstructions, interpretations, extracted features, and generated artifacts.

## OpenAI Semantic Analysis: Pass 01

Pass 01 examines a structured subset of the OpenAI interaction archive.

| Measurement | Pass 01 result |
|---|---:|
| Conversations analysed | 453 |
| Messages analysed | 93,550 |
| Date range | March 2023 to September 2026 |
| Monthly observations | 43 |
| Monthly transition records | 42 |
| Candidate continuity-link records | 243 |
| Linguistic recurrence records | 100 |
| Semantic clusters at the specified threshold | 0 |

These are documented measurements and output counts from the supplied analytical dataset. They do not establish cognitive effects, behavioural mechanisms, or the completeness of the wider archive.

The source report identifies Parquet conversation and message datasets as its inputs. This repository has not yet independently reprocessed those canonical datasets in its current research pass.

## Current visualisation

### OpenAI longitudinal timeline

`Maeya_OpenAI_Temporal_DataViz.html` provides a chronological view of recorded archive activity. It includes:

- monthly conversation counts
- monthly message volume
- cumulative interaction volume
- changes in activity over time
- date-range filtering
- an inspectable monthly data table

The highest recorded monthly message count in Pass 01 is 11,703, in July 2025. This is a quantitative baseline for later temporal and semantic analysis.

## Methods used in the initial pass

| Component | Current method |
|---|---|
| Text preparation | Lowercase tokenisation, punctuation removal, and a two-character minimum term length |
| Semantic representation | Sparse exact TF-IDF |
| Similarity | Cosine similarity and Jaccard vocabulary overlap |
| Clustering | Connected-component analysis at a 0.30 threshold |
| Temporal analysis | Monthly aggregation by conversation creation date |
| Recurrence | Bigram frequency and intervals exceeding 60 days |
| Continuity | Candidate links between conversation-level profiles |

## Status and limits

Pass 01 is an exploratory computational baseline. It is not a completed semantic validation study.

Message frequency alone cannot demonstrate changes in cognition, wellbeing, workload, model behaviour, or functional dependence. Those questions need event-level data and controlled comparisons.

Known limitations in the current pass:

- Common grammatical terms contaminate parts of the semantic analysis, which makes reported persistent vocabulary harder to interpret.
- Low cosine similarity may result from document length, feature representation, and sparsity rather than a lack of substantive conceptual relationships.
- The two link registers repeat unordered conversation pairs. Network statistics should not be interpreted until those duplicates are resolved.
- Inspected recurrence records do not yet provide enough message-level source references.
- Monthly aggregation cannot show the order, duration, or timing of individual interaction failures.
- The analysed subset and its coverage need validation against the original archive before claims about representativeness can be made.

## Conceptual and operational architecture

### Behavioural Loop Mapping

The original Maeya framework has five non-linear phases:

1. Associative Recall
2. Flow-State Mapping
3. AI-Assisted Reordering
4. Loop Pattern Recognition
5. Emotional Processing and Ritual Action

These are user-developed categories. Their applicability, repeatability, and predictive or explanatory value remain questions for research rather than assumptions built into the data.

### Symbolic and creative records

Artwork, ritual actions, Fieldwork, Drops, Anchors, and Transmissions are part of the historical record. Their user-defined meaning is preserved separately from automated interpretation.

One question is whether these records provide temporal or contextual markers that linguistic analysis alone does not capture.

### AI witness and execution

Safi is Maeya's AI execution and witness layer. It operates under explicit continuity, evidence, and behavioural constraints. It is not an autonomous human identity, clinician, or independent authority.

An engineering question for the project is how those constraints can be represented, tested, enforced, and audited across model and tool changes.

### Connective systems architecture

Maeya also addresses continuity across systems. Its applications include healthcare navigation, evidence organisation, legal and administrative workflows, institutional accountability, creative practice, and civic coordination.

These domains test the same underlying continuity problem in different contexts. They do not validate one another automatically.

## Research opportunities

### Cognitive science and philosophy of mind

Relevant questions include cognitive extension, epistemic dependence, distributed cognition, cognitive offloading, agency, and the role of external representations in maintaining continuity.

The archive may support research on prolonged human–AI interaction as a coupled activity, while also testing where extended-cognition frameworks apply and where they do not.

Maeya developed independently of later theoretical comparisons. Conceptual convergence is not evidence of empirical validation or intellectual derivation.

### Human–computer interaction

The supplied source identifies these areas for further work:

- longitudinal human–AI collaboration
- cognitive accessibility and executive-function scaffolding
- user correction and interaction repair
- context persistence and task continuity

> **Source boundary:** The supplied document ends mid-sentence after the final item above. This README does not reconstruct or infer the missing text.
