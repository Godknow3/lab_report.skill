# Evidence Mapping and Final Audit

Read this reference when creating, filling, or auditing a complete report.

## Evidence map

Before drafting, record the minimum traceability table:

| Report section or claim | Requirement source | Theory source | Code location | Parameters | Input | Output evidence | Status |
|---|---|---|---|---|---|---|---|

Use `verified`, `missing`, or `conflicting` for status. Do not silently convert missing evidence into prose.

For each experiment result, capture:

1. Operation: what code actually did.
2. Observation: what can be seen or measured in the output.
3. Explanation: why the operation produced that observation.
4. Limitation: noise, clipping, alignment, sampling, parameter sensitivity, or another material constraint when relevant.

## Code selection

Include excerpts that establish the algorithm and parameters. Omit imports, repeated saving calls, boilerplate, and unrelated utilities unless they are essential to reproducibility. Explain the data flow around the excerpt instead of narrating every line.

## Figure rules

- Use only actual inputs and outputs from the experiment.
- Pair comparison images at compatible scales when possible; follow [word-figure-layout.md](word-figure-layout.md) for Word placement and page-break control.
- Preserve aspect ratio; do not stretch screenshots.
- Use sequential numbering and descriptive captions.
- Cite each figure in nearby prose and explain a visible feature.
- Avoid inserting multiple images that provide the same evidence.

## Content audit

- Every required task and question is answered.
- Titles, formulas, terminology, units, and parameter values are consistent.
- Code excerpts match the current project.
- Observations match the shown figures or measured data.
- Claims do not exceed the evidence.
- Personal information appears only where the template requires it.
- References are real and traceable.

## Document audit

- Preserve the supplied template's structure and styles unless redesign was requested.
- Check headings, tables, formulas, code blocks, captions, page breaks, headers, footers, and numbering.
- Check every rendered page for clipping, overlap, distortion, broken characters, orphan headings, and unintended blank pages.
- Re-render after any material correction.
