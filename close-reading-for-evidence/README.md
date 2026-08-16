# Close Reading for Evidence

Standalone GitHub repository for the Main textbook skill `SKILL-CR` and competency `COMP-CR-EVIDENCE`.

This repository is self-contained. Upload this folder as the repository root; do not upload only `references/`. The root includes `SKILL.md`, Codex UI metadata, the full competency and assessment codification, evaluator specification, output schema, handoff contract, provenance and authorship guidance, source manifest, shared schemas, fixtures, validation scripts, CI, release metadata, and checksums.

## Canonical design trace

`SPEC-CR-001` · `ANRI-DOM-CR-001` · `ARCH-CR-001` · `CORP-CR-001`

The package is finalized as a private draft. Its evaluator is intentionally `CONDITIONAL` where human review is required for interpretation, authorship, currentness, rights, and transfer to Writing or Argumentation. It does not invent passages, quotations, locators, context, or author intent.

## Validate locally

```text
python scripts/validate_repository.py
python scripts/validate_repository.py --check
python scripts/evaluate_package.py
python scripts/build_release_manifest.py --check
```

The canonical textbook source files remain external and are mapped, not copied, in `catalog/source-manifest.json`.
