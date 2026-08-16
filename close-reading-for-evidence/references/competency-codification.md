# Close Reading competency codification

**Competency:** `COMP-CR-EVIDENCE`  
**Domain:** `DOM-CR` / `SKILL-CR`  
**Governing protocol:** `SPEC-COMP-001`  
**Technical specification:** `SPEC-CR-001`  
**Prompt:** `ANRI-DOM-CR-001`  
**Architecture:** `ARCH-CR-001`  
**Corpus:** `CORP-CR-001`

## Construct

Build a traceable interpretation of a supplied text or representation by setting a reading purpose, locating relevant language or features, distinguishing observation from inference, explaining how textual or graphical choices produce meaning, qualifying claims when context is incomplete, and preserving enough provenance for another reader to inspect the reasoning.

## Observable performances

| ID | Performance |
|---|---|
| `OP-CR-01` | State task, audience, and reading purpose. |
| `OP-CR-02` | Locate relevant passage, feature, or graphic element with a stable locator. |
| `OP-CR-03` | Record direct observation before interpretation. |
| `OP-CR-04` | Explain an inference or interpretation and its warrant. |
| `OP-CR-05` | Analyze applicable structure, language, perspective, evidence, and representation choices. |
| `OP-CR-06` | Compare sources or representations without erasing genre, authority, or scale differences. |
| `OP-CR-07` | Record uncertainty, missing context, source conflict, and alternatives. |
| `OP-CR-08` | Transfer a checked evidence record into writing, argumentation, or inquiry. |

## Functional-requirement trace

| ID | Canonical requirement and acceptance focus |
|---|---|
| `FR-CR-01` | Segment supplied text into meaningful units with recoverable locators; every observation resolves to one supplied unit. |
| `FR-CR-02` | Separate explicit text, observation, inference, interpretation, and outside knowledge; unsupported context claims are flagged. |
| `FR-CR-03` | Extract evidence with context and provenance; promoted evidence has source ID, locator, language type, and status. |
| `FR-CR-04` | Analyze word choice, structure, perspective, argument, and medium when relevant; mark non-applicable analyses rather than inventing them. |
| `FR-CR-05` | Produce an alternative, contradiction, or uncertainty when warranted; conflicting-source fixtures are preserved. |
| `FR-CR-06` | Support literature, informational, technical, legal/policy, research, and multimodal text modes without changing the evidence schema. |
| `FR-CR-07` | Create a learner-produced evidence artifact such as a ledger, annotation, discussion move, or exit task. |
| `FR-CR-08` | Preserve learner authorship in AP modes; ghostwriting requests return scaffolds or a refusal, not a submission. |
| `FR-CR-09` | Use AP Seminar and historical CED sources as calibration for source reasoning, perspective, credibility, and attribution, not as a universal close-reading rubric. |

## Project diagnostic dimensions

These are project-defined diagnostics, not an invented official score scale: locator accuracy; observation/inference distinction; interpretation warrant; source/representation fit; qualification; and transfer readiness.

## Source and assessment boundaries

The authority stack includes Common Core and official current-site sources (`S003`, `S006`), SAT technical and operational sources (`S002`, `S007/S008`, `S099`), Smarter Balanced/PARCC lineage (`S101/S121`, `S100`), ACRL and primary-source literacy (`S102/S104`), GRE discourse analysis (`S103`), reader-text-context theory (`S018`), and bounded expansion comparators (`S134`, `S135`). These sources provide outcome, assessment, context, or comparison evidence; none authorizes an invented universal close-reading rubric. Secure stimuli, protected samples, and current claims remain rights/currentness controlled.

## Evidence and release conditions

The evidence record must preserve `source_id`, locator, observation, interpretation, claim status, uncertainty, provenance, and learner decision. `TST-CR-001` through `TST-CR-008`, `TST-INT-001`, and `TST-INT-002` are required. Open conditions include grade/course locator confirmation, licensed exemplars, separated literary/informational/disciplinary/multimodal evidence, and human review of CR-to-WR/ARG transfer.
