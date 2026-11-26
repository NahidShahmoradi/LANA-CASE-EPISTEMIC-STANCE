# Methodology

## 1. Research design

This project investigates the pragmatic and interactional functions of epistemic stance markers in spontaneous American English conversation. It adopts a mixed qualitative–quantitative design: computational procedures support the retrieval and organisation of relevant records, while contextual and pragmatic interpretation is carried out through manual annotation.

The analysis is not limited to counting marker forms. It considers how speakers use epistemic expressions to present knowledge, uncertainty, belief, inference, possibility, and personal assessment, and how these expressions operate in interaction.

## 2. Corpus and data

The study uses material from the LANA-CASE spoken American English corpus. The working dataset contains 100 selected sample records associated with the following ten target markers:

- *I think*
- *I know*
- *I don't know*
- *maybe*
- *probably*
- *I guess*
- *could*
- *might*
- *must*
- *I thought*

The corpus materials available for the project include spoken-language records and associated sample/speaker metadata. Corpus metadata are used as contextual information where relevant; they are not treated as evidence for a speaker's intentions or stance by themselves.

Before public release, the corpus version, formal corpus citation, access conditions, and licence terms should be stated here using the corpus provider's documentation. Original transcripts, audio, and identifying speaker information should not be redistributed unless the corpus terms explicitly permit it.

## 3. Sample selection

A working set of 100 records was assembled to provide coverage across the ten target marker forms. The selection is marker-oriented rather than a random sample of the full corpus. Accordingly, the 100 records are used for an exploratory, marker-focused analysis and are not assumed to be statistically representative of all LANA-CASE conversations or of spoken American English more generally.

The sample-flow record distinguishes between records retained for the core epistemic analysis and records excluded from that analysis. In the current reviewed dataset:

- 100 records are present in the working sample.
- 93 records are eligible for the core analysis when confirmed and provisional cases are considered together.
- Within those 93 records, 53 are marked as confirmed and 40 as provisional.
- Samples 070 and 071 are retained in the dataset as non-epistemic controls but excluded from the core epistemic analysis.

Provisional cases are retained transparently rather than being silently treated as fully confirmed. Any additional exclusions or unresolved cases are documented in the accompanying coding workbook and codebook.

## 4. Units and levels of analysis

The project keeps two annotation levels separate:

1. **Sample-level epistemic stance analysis.** Each selected record is examined in its conversational context to determine whether and how an epistemic stance is expressed. Broad stance-family labels are used as organising categories; draft or unresolved labels remain flagged rather than being forced into a definitive theoretical taxonomy.
2. **Interactional-response analysis.** The response or uptake associated with the relevant contribution is coded separately (for example, acknowledgement, agreement, disagreement, elaboration, or information provision). This layer describes the interactional response and is not itself an epistemic stance category.

The two layers are not interchangeable. An acknowledgement, for example, does not automatically establish agreement with the epistemic content of the preceding turn.

A separate token inventory was generated as an auxiliary aid. It contains 114 literal marker occurrences across the 100 records (107 within the 93 core-eligible records). These entries are extraction candidates, not completed token-level pragmatic annotations: all 114 occurrences remain marked as requiring occurrence-level validation. Sample-level labels must therefore not be presented as if they were independently verified labels for every occurrence within a sample.

## 5. Retrieval and annotation procedure

The working records were organised computationally, including the use of Python-based text processing to support marker retrieval and inventory construction. The token inventory uses case-insensitive matching with word-boundary checks against the recorded target marker form. This procedure identifies candidate string occurrences; it does not determine their pragmatic function.

The sample-level analysis was then conducted through contextual manual review. Decisions take account of the surrounding conversational context and the function of the expression in its local interaction. The annotation process distinguishes epistemic uses from non-epistemic uses and preserves uncertainty where the available context does not support a confident interpretation.

The coding workbook records inclusion decisions, confidence/review flags, broad stance-family labels, and interactional-response codes. The accompanying codebook documents the labels and distinctions used in the working annotation. User-reviewed corrections are retained in the reconciled dataset; unresolved, low-confidence, and unmapped cases remain visible.

## 6. Analytical approach

The analysis combines:

- descriptive examination of the distribution of the target markers in the selected sample;
- qualitative interpretation of their local epistemic and pragmatic functions;
- comparison of markers that appear to perform related or contrasting functions; and
- separate examination of interactional responses.

The marker-level synthesis considers contrasts such as *I think* and *I guess*, *I know* and *I don't know*, *maybe*, *might* and *could*, and *probably* and *must*. These comparisons are interpretive and context-sensitive; they are not treated as fixed one-to-one mappings between a form and a single meaning.

No numerical certainty or commitment scale is imposed in the current analysis. Likewise, no inferential statistical test or inter-annotator reliability coefficient is reported in this version.

## 7. Scope and limitations

Several limitations should guide interpretation:

- The 100-record dataset is marker-oriented and exploratory, not a random or representative sample of the full corpus.
- The presence of a target string does not guarantee an epistemic use; contextual manual interpretation is necessary.
- The token inventory is a retrieval aid and remains pending occurrence-level validation.
- Some sample-level classifications are provisional, low-confidence, or unmapped. These are retained as such in the data.
- Broad stance-family labels are working analytical categories, not a final universal taxonomy of epistemic stance.
- Interactional-response coding describes conversational uptake and should not be conflated with the speaker's epistemic commitment.
- Findings should be interpreted in relation to the selected records and target markers, not generalised to all spontaneous American English.

## 8. Reproducibility and data availability

The repository should provide the project code, documentation, codebook, and appropriately anonymised or derived annotation tables where permitted. The raw corpus transcripts, audio, and speaker-identifying metadata should remain outside the repository unless the corpus provider's licence and privacy conditions explicitly allow redistribution.

For reproducibility, the repository should identify the corpus source and version, document any preprocessing scripts, and distinguish between (a) source-derived records, (b) manually reviewed sample-level annotations, and (c) the preliminary token-occurrence inventory.
