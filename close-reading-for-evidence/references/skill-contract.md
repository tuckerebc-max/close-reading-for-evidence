# Close Reading package contract

**Registry ID:** `SKILL-CR`  
**Package version:** `0.1.0`  
**Source domain:** `DOM-CR`  
**Current status:** `READY_WITH_CONDITIONS`

## Required inputs

Supply a readable text or corpus, recoverable locator system, purpose, grade band or course, target reading move, output mode, and access constraints. A missing or incomplete source stops the run.

## Core payload

The package produces `source_units`, `evidence_units`, `observations`, `interpretations`, `alternative_or_uncertainty`, `learner_task`, and `next_action` inside the shared artifact envelope.

## Quality conditions

Every promoted evidence unit resolves to a supplied source and locator. Explicit content, observation, inference, interpretation, outside knowledge, and learner decision remain distinct. Applicable analysis dimensions are selected rather than assumed. Conflict, uncertainty, rights, accessibility, and authorship are visible.

## Canonical source paths

See `catalog/source-manifest.json` for the portable mapping to the prompt, corpus crosswalk, competency design specification, technical specification, and textbook architecture. The source validation IDs are `TST-CR-001` through `TST-CR-008`, plus `TST-INT-001` and `TST-INT-002`.
