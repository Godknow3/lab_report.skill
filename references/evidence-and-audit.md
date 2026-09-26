# Evidence Mapping and Final Audit

Read this reference when creating, filling, or auditing a complete report.

## Evidence map

Before drafting, record the minimum traceability table:

| Report section or claim | Requirement source | Theory source | Code location | Parameters | Input | Output evidence | Status |
|---|---|---|---|---|---|---|---|

Use `verified`, `missing`, or `conflicting` for status. Do not silently convert missing evidence into prose.

Record whether evidence was generated in this task or supplied from an earlier run. A matching filename alone does not establish that an output came from the current code and parameters. Keep the map in working notes or an existing audit artifact; do not add a separate deliverable solely to satisfy this schema.

For each experiment result, capture:

1. Operation: what code actually did.
2. Observation: what can be seen or measured in the output.
3. Explanation: why the operation produced that observation.
4. Limitation: noise, clipping, alignment, sampling, parameter sensitivity, or another material constraint when relevant.

## Code selection

Include excerpts that establish the algorithm and parameters. Omit imports, repeated saving calls, boilerplate, and unrelated utilities unless they are essential to reproducibility. Explain the data flow around the excerpt instead of narrating every line.

## Execution and validation

- For algorithm changes or newly generated results, run the relevant experiment and check observable properties: dimensions, data types, value ranges, reconstruction error, or extraction accuracy as appropriate to the task.
- Use existing tests, numerical assertions, or a small reproducible check. Add unit tests when they meaningfully protect changed behavior; wording and layout edits do not require new code tests.
- Inspect saved outputs as well as exit status. Record the command, relevant parameters, checks, and outcome in the evidence notes. Do not describe a historical run as a run performed in this task.
- Keep supplied originals and unrelated results intact. Use distinct outputs when reproducing an experiment would overwrite evidence that still needs comparison.

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

## Skill regression scenarios

When maintaining this skill, use these representative requests to review behavior. Structural validation alone cannot establish that an agent follows them; mark scenarios as executed only after actually exercising them.

| Request and available evidence | Expected observable behavior |
|---|---|
| Complete a report from a template, runnable code, and local inputs | Produce the requested report; trace its results to artifacts; complete content and rendered-page checks. |
| Review an existing report without editing it | Return findings with locations and evidence; leave report and experiment files unchanged. |
| Revise only the wording of the analysis | Preserve facts, parameters, figures, and scope; avoid unrelated experiment runs; render if modifying Word output. |
| Fill results, but an essential input is unavailable | Finish independent sections, identify the missing input, and label unsupported results as unverified; do not claim completion. |
| The assignment specifies method A, but artifacts were produced with B | Expose the mismatch; correct and rerun only when authorized; never relabel B's output as A's. |
