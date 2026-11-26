# CODEBOOK — LANA-CASE Epistemic Stance Project


## 1. Purpose and scope

This codebook documents the coding structure used in a marker-balanced pilot sample of 100 manually selected records from LANA-CASE. The sample is not a random sample and is not intended to estimate corpus-wide prevalence.

The project examines these ten target expressions:

- `I think`
- `I know`
- `I don't know`
- `maybe`
- `probably`
- `I guess`
- `could`
- `might`
- `must`
- `I thought`

The workbook preserves the original source columns and adds review-oriented fields. In particular, the stance-family field is explicitly a **draft organising label**, not a finalized theoretical taxonomy.

## 2. Unit and layers of analysis

The workbook contains 100 sample records. A record may discuss more than one occurrence of a target expression; where the notes identify multiple tokens within one sample, those occurrences must not be collapsed without justification.

Three dimensions are kept separate:

1. **Epistemic / pragmatic interpretation:** the contextual interpretation recorded in `Epistemic / pragmatic analysis`.
2. **Draft epistemic stance family / proposed coding:** organising labels and proposed codes used to review the interpretation.
3. **Interactional response:** the separate field `Interactional_Response_Final`, which records the response code. Acknowledgment or alignment does not automatically constitute epistemic commitment.

## 3. Inclusion decisions

The workbook's `Decision` field contains the following categories:

| Decision value | Number of records | Treatment |
|---|---:|---|
| `Include` | 53 | Included in the core analysis as confirmed cases |
| `Include (Provisional)` | 40 | Retained in the core set but explicitly flagged as provisional |
| `Exclude` | 4 | Excluded from the core analysis |
| `Exclude from core epistemic analysis; retain as non-epistemic control` | 3 | Retained in the raw dataset as controls; excluded from the core epistemic analysis |
| **Total** | **100** | |

Thus, the core set (`Include` + `Include (Provisional)`) contains 93 records. The confirmed-only sensitivity subset contains 53 records.

The four explicit exclusions in the workbook's `Sample_flow` sheet are samples 081, 083, 086, and 090. The three non-epistemic controls are sample 096 and user-confirmed samples 070 and 071. Samples 070 and 071 must remain in the raw data as controls, while being excluded from the core epistemic analysis.

## 4. Confidence

The `Confidence` field records the confidence level attached to the contextual interpretation. Values present in the workbook are:

- `High`
- `Medium–High`
- `Medium`
- `Low–Medium`
- `Medium–Low`
- `Low`

The workbook does not define these as a calibrated numerical scale. Preserve the original wording and do not convert these values into numbers or infer equal intervals between them.

## 5. Draft epistemic stance families

The workbook's `Draft_Epistemic_Stance_Family` field contains the following labels. The `Coding_Guide` sheet explicitly states that these are broad organising labels inferred from the existing `Epistemic / pragmatic analysis` text; they are **not** a finalized theoretical taxonomy.

| Draft stance-family label | Records in `Review_All_100` |
|---|---:|
| `Possibility / tentative hypothesis` | 26 |
| `Epistemic inference / possible explanation` | 13 |
| `Interactional acknowledgment / alignment (epistemic status context-dependent)` | 11 |
| `Past belief / expectation` | 9 |
| `Tentative belief / personal assessment` | 8 |
| `Probability / likelihood assessment` | 7 |
| `Uncertainty / lack of certainty` | 6 |
| `Knowledge / lack of knowledge` | 6 |
| `Non-epistemic necessity/intention (exclude)` | 6 |
| `Context-dependent / requires manual classification` | 4 |
| `Tentative proposal / intention (check epistemic status)` | 2 |
| `Non-epistemic / no epistemic stance (user correction)` | 2 |

These are workbook labels, not mutually validated final categories. In particular, preserve context-dependent and non-epistemic labels rather than forcing them into an epistemic family.

## 6. Proposed primary codes

`Proposed_Primary_Code_v1` is a **proposed/review field** in the workbook, not a fully finalized codebook mapping. The following code values occur in that field:

| Code as recorded | Broad interpretation supported by workbook examples | Status / caution |
|---|---|---|
| `POSS` | Possibility or tentative possibility | Proposed code; examples include possible outcomes and alternatives |
| `INFR` | Inference or possible explanation | Proposed code; examples include conclusions drawn from contextual evidence |
| `TENT` | Tentative stance or tentative assessment | Proposed code; includes tentative personal assessments |
| `PRED` | Prediction or projection about a possible future event | Proposed code |
| `RECALL` | Recalled past belief or expectation | Proposed code, especially for `I thought` |
| `LACK` | Lack of knowledge or specific information | Supported by user-confirmed cases; preserve distinctions between separate occurrences |
| `INT` | Tentative intention, proposal, or preference | Proposed code; epistemic status may require contextual checking |
| `MIT` | Mitigating function / mitigation of a personal evaluation or stance | Appears as a primary code in a user-confirmed case; do not equate automatically with literal lack of knowledge |
| `EPI-LIM` | Epistemic limitation, including limits on predicting a future outcome | Appears in proposed secondary-function notes and code examples; mapping should be checked against the project's full codebook before treating as finalized |
| `EXCLUDE` | Case excluded from the core epistemic analysis | Used for non-epistemic necessity, intention, or other non-core cases |
| `UNMAPPED` | No secure mapping to the current code scheme | Retain as unresolved; do not force a category |

The workbook also contains descriptive variants in the proposed field, such as `LACK (both occurrences)` and `TENT — Tentative stance`. These preserve sample-specific detail and should not be silently normalized when the distinction matters.

**Important:** The workbook's `Coding_Guide` does not provide formal operational definitions or exhaustive decision rules for every primary code. The interpretations in the table above are deliberately limited to what is supported by the sample analyses and coding notes.

## 7. Proposed secondary functions

The field `Proposed_Secondary_Function_v1` records secondary functions or more specific notes where applicable. Values in the workbook include:

- `MIT`
- `ACKN`
- `EPI-LIM`
- `INT`
- `Lack of specific locational knowledge`
- `Direct expression of not knowing`
- `Limited knowledge`
- `Mitigation of an affective/personal evaluation`
- `Uncertainty / lack of certainty`
- `Uncertainty / lack of specific information; second occurrence followed by an approximate answer`
- `Lack of knowledge; 'either' aligns with the prior speaker's lack of knowledge`

These entries are not all codes at the same level: some are abbreviations and some are explanatory descriptions. Preserve them as recorded unless a separate, explicitly approved normalization scheme is supplied.

## 8. Interactional-response coding

The workbook stores interactional response separately in `Interactional_Response_Final`. Values present include:

- `ACK`
- `AGR`
- `CLR`
- `DIS`
- `ELA`
- `INF`
- `NR`
- `OTH`
- `MISSING`

The uploaded workbook contains these labels and their sample-level assignments, but its `Coding_Guide` sheet does **not** provide full operational definitions or expansions for every abbreviation. This document therefore does not invent expansions for `ELA`, `INF`, or `CLR`, or detailed boundaries between response categories.

The workbook distinguishes missing next-turn context from an observed response. The `Sample_flow` sheet records 5 core records with missing next-turn context and 88 core records with an observable next-turn response. `MISSING` and `NR` should not be treated as interchangeable without consulting the original interactional coding rules.

### Confirmed interactional-response corrections from the project record

The following manually validated decisions must be preserved:

- Sample 051 = `ACK` (not `ELA`)
- Sample 074 = `DIS`
- Sample 098 = `ACK`
- Sample 099 = `DIS`
- Sample 100 = `ACK`

These response labels remain independent of epistemic stance coding.

## 9. Review fields and status labels

The review-oriented fields in `Review_All_100` include:

- `Review_Priority`
- `Reviewer_Decision`
- `Reviewer_Comments`
- `Proposed_Primary_Code_v1`
- `Proposed_Secondary_Function_v1`
- `Coding_Note_v1`
- `Coding_Status_v1`

Values in `Review_Priority` include:

- `Routine check`
- `Review — provisional/low confidence`
- `Review exclusion boundary`
- `HIGH — apply user correction`

The workbook's `Coding_Status_v1` includes statuses such as `Proposed`, `Provisional`, `User-confirmed`, `User-approved`, `Excluded`, and more specific unresolved/review variants. These statuses indicate the review state of the proposed coding. They should not be collapsed into the `Decision` field: inclusion status, confidence, and coding-review status are distinct dimensions.

`Reviewer_Decision` and `Reviewer_Comments` are fields for recording review decisions and explanations. A blank reviewer field does not itself establish that a proposed code has been approved.

## 10. Confirmed sample-specific decisions and safeguards

The workbook's coding notes and project decisions require the following distinctions to be retained:

- Sample 021: `I don't know` is coded as lack of knowledge (`LACK`); interactional response remains separate.
- Sample 022: `I don't know` is coded `LACK`; interactional response is `MISSING` pending separate review.
- Sample 023: `I don't know` has a mitigating function (`MIT` as primary), not literal lack of knowledge.
- Sample 024: `I don't know` is `LACK`, specifically lack of knowledge about where the item is; do not conflate it with the following `I think`.
- Sample 025: the functional interpretation is uncertainty; the note says not to force a final primary-code mapping until checked against the codebook.
- Sample 026: limited knowledge, contrasting with the preceding `I know what it is`.
- Sample 027: uncertainty about future coping ability / limitation in predicting a future outcome.
- Sample 028: lack of specific locational knowledge.
- Sample 029: tentative personal stance with a mitigating function; do not interpret as literal lack of knowledge.
- Sample 030: two distinct `I don't know` occurrences; both are coded `LACK` in the user-confirmed note and must remain separate within the sample.
- Sample 070 and 071: user-confirmed non-epistemic controls; exclude from the core epistemic analysis but retain in raw data.
- `I guess` may function as **direct agreement** in response to another speaker; do not automatically recast it as indirect agreement.

Where a sample contains multiple occurrences, preserve token-level distinctions recorded in the workbook. Do not collapse them into one occurrence merely because they appear in one sample record.

## 11. Commitment and certainty

The `Coding_Guide` explicitly states that no new commitment or certainty scale has been imposed. Qualitative descriptions such as relatively strong commitment or tentative assessment may appear in individual sample analyses, but they do not constitute a numerical scale. Do not add a numerical certainty score unless a separate framework is explicitly agreed.

## 12. Corpus and data-sharing restrictions

LANA-CASE is a licensed corpus, not public-domain material. Do not upload raw corpus files, transcripts, audio, speaker-level metadata, record-linked annotation exports, or modified corpus material to the public repository unless the rights holders have explicitly authorised that redistribution. Repository documentation should describe the research design and coding framework without reproducing licensed corpus content.

## 13. Known limits of this workbook-based codebook

The uploaded workbook supports the coding architecture, category values, sample-level assignments, and the project-specific decisions documented above. It does not, by itself, provide a complete formal definition list for every abbreviated interactional-response code or every proposed primary/secondary code.

Accordingly:
- Proposed stance families remain draft organising labels.
- `Proposed_*_v1` fields remain proposed coding fields unless a row's status/notes explicitly records user confirmation or approval.
- Abbreviations in the interactional-response field are listed without invented expansions.
- Ambiguous, provisional, low-confidence, unmapped, and codebook-gap cases remain visible.
- No numerical commitment/certainty scale is added.

## 14. Corpus references

Hanks, E., McEnery, T., Egbert, J., Larsson, T., Holmberg, A. J., Biber, D., Reppen, R., Baker, P., Bottini, R., Brezina, V., Brookes, G., & Clarke, I. (2026). Introducing the Lancaster-Northern Arizona Corpus of American Spoken English (LANA-CASE). *Corpora*.

Hanks, E., McEnery, T., Egbert, J., Larsson, T., Biber, D., Reppen, R., Baker, P., Brezina, V., Brookes, G., Clarke, I., & Bottini, R. (2024). Building LANA-CASE, a spoken corpus of American English conversation: Challenges and innovations in corpus compilation. *Research in Corpus Linguistics, 12*(2), 24–44. https://doi.org/10.32714/RICL.12.02.03

Corpus access and licence information: https://cass.lancs.ac.uk/lana-case/
