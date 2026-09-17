# Natural Technical Writing

Read this reference only when drafting report prose, reducing formulaic AI style, or performing a final language pass.

## Target voice

Write as a careful undergraduate reporting work actually completed. Prefer direct, specific sentences grounded in code and observed results. Keep terminology accurate without inflating the significance of a routine teaching experiment.

## Revision rules

- Preserve formulas, parameter values, filenames, observations, and causal explanations.
- Remove generic openings, repeated conclusions, and ceremonial phrases that add no evidence.
- Do not force every paragraph into “first, second, finally” or “through this experiment” patterns.
- Let section and paragraph length follow the amount of real evidence. Do not make every task, subsection, list item, or result analysis occupy a visually similar amount of space merely for symmetry.
- Give more space to an operation with several parameters, intermediate results, or visible limitations; keep a simple operation concise. Do not pad short sections to match long ones.
- Vary sentence structure naturally, but do not manufacture personal anecdotes, hesitation, mistakes, or informal speech to appear human.
- Use first person only when the template or course convention favors it; otherwise use neutral descriptions.
- Prefer “the threshold mask contains fragmented edges because…” over “the method achieved a good effect.”
- Avoid unsupported intensifiers such as “significantly,” “perfectly,” “fully,” and “strongly proves.”
- Explain a limitation when it is visible and relevant rather than presenting every output as successful.
- Use em dashes and dash-led explanatory clauses sparingly. Prefer a full stop, comma, colon, or a short follow-up sentence when the relationship remains clear.
- Avoid repeatedly using the pattern “术语——解释” or “结论——原因”. It is acceptable occasionally, but it should not become the report's dominant sentence shape.

## Chinese, English, and punctuation

- Do not append an English translation to every technical term. Add it only at the first occurrence when it helps identify a standard term or matches course materials; later use the Chinese term or established abbreviation.
- For a parenthetical English term inside Chinese prose, prefer half-width parentheses without internal padding, for example `双线性插值 (Bilinear Interpolation)`. Do not write `（ Bilinear Interpolation ）`.
- Keep Chinese sentence punctuation in Chinese form. Use half-width punctuation inside code, formulas, filenames, parameter expressions, and English-only fragments.
- Be consistent within a local context, but do not mechanically force every term into the same “中文 (English)” pattern.
- Avoid conspicuous spacing around punctuation. Do not insert spaces merely to simulate typing habits.

## Paragraph formatting

- Preserve the report template's paragraph settings.
- If no template defines body paragraphs, default ordinary body text to no first-line indentation. Use modest paragraph spacing or natural paragraph breaks instead of an automatic two-character indent.
- Make the no-indent choice in the Word paragraph style or paragraph properties so pressing Enter creates another paragraph without inherited leading space.
- If an existing paragraph keeps indenting after Enter, clear the paragraph's first-line indent or modify the inherited body-text style; do not try to erase it as if it were typed spaces.
- Never use repeated spaces or full-width spaces to simulate first-line indentation or alignment. Such spacing is unstable when fonts, margins, or line wrapping change.
- Do not intentionally introduce punctuation mistakes, random indentation, inconsistent fonts, or other fake “human traces.” Naturalness should come from evidence-weighted structure and specific observations.

## Paragraph pattern for results

A useful result paragraph usually contains:

1. the operation and relevant parameter;
2. a concrete observation from the figure or data;
3. the technical reason for the observation;
4. an important limitation or comparison, if present.

Do not repeat this as a rigid four-sentence template. Combine or omit elements when the evidence does not require them.
