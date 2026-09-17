# Word Figure Layout for Lab Reports

Read this reference whenever a Word report contains experiment images, screenshots, plots, diagrams, or before/after comparisons.

## Plan before insertion

Make a figure plan from the evidence map. For every figure or comparison group, identify:

- the report subsection it supports;
- the observation the reader should notice;
- whether comparison requires equal visual scale;
- the shortest caption that identifies operation and parameter;
- whether the figure must stay with a nearby paragraph or formula.

Do not append all images at the end of a task. Place each figure immediately after the paragraph that introduces it, followed by the paragraph that analyzes it.

## Choose a layout by comparison purpose

- Use one centered figure when fine detail matters, the image contains text, or it is the primary result.
- Use a two-column comparison for original/result, input/output, or two parameter settings. Keep both images at equal displayed height or equal scale when the comparison depends on size.
- Use a compact 2-by-2 grid for three or four closely related outputs only when every image remains legible. Otherwise split the group across separate rows or pages.
- Avoid more than two detailed images per row. Do not shrink figures merely to reduce page count.
- For a processing sequence, order figures in the same direction as the algorithm: input, intermediate result, final result.
- Keep sizing restrained. A routine result does not need to fill the page, while a detailed plot or screenshot should not be reduced until its content becomes difficult to read.

For stable Word layout, prefer inline images. A borderless table may be used for side-by-side comparisons when ordinary paragraph placement shifts unpredictably, but do not turn every figure into a boxed card or visible table. Keep the final appearance plain and appropriate for a course assignment.

## Sizing and quality

- Determine usable width from page size and margins; never exceed it.
- Preserve the original aspect ratio and set only one dimension unless a crop is intentional.
- Do not enlarge a low-resolution raster image until it becomes visibly soft or pixelated.
- Crop irrelevant application chrome and empty margins from screenshots when doing so does not hide evidence.
- Keep text inside plots and screenshots readable at the final physical size.
- Use the same width, crop, and alignment for images intended for direct comparison.
- Prefer original output files over screenshots of those files.

## Captions and references

- Put figure captions below figures and table titles above tables unless the supplied template specifies otherwise.
- Number figures consistently across the document or within chapters, following the template.
- Keep ordinary lab-report captions concise. Name the object or operation and include a parameter only when it distinguishes the result, for example `图3 绝对差分结果` or `图8 Gamma=0.5时的处理结果`.
- Do not turn a caption into a complete analysis sentence. Put interpretation in the surrounding paragraph.
- Avoid adding source-like, method-like, or overly formal qualifiers to every caption when the nearby heading already establishes the experiment context.
- Use plain caption text below the image. Do not add a border, shaded label box, decorative line, colored card, or oversized caption unless the supplied template already uses that style.
- Short course reports do not require automatic Word captions and cross-references unless the template, teacher, or document length makes them useful. A correctly numbered plain caption is sufficient when it remains stable after editing.
- Refer to every figure in nearby prose, such as “如图3所示”, and describe at least one visible feature.
- For a grouped comparison, use either one group caption with clear subfigure labels `(a)`, `(b)`, or separate captions; do not mix both systems inconsistently.

## Page-break control

- Keep an image with its caption. Avoid a caption alone at the top or bottom of a page.
- Keep a subsection heading with the first explanatory paragraph; do not leave a heading stranded at the page bottom.
- Avoid splitting a comparison grid across pages. Move the complete group to the next page when needed.
- Do not force an image into remaining whitespace if it makes the image unreadable; use an intentional page break.
- Prevent large unexplained blank areas. A small blank area is acceptable when it preserves a comparison group or heading hierarchy.

## Visual QA loop

After each meaningful document update:

1. render the complete DOCX to page PNGs using the document-authoring workflow;
2. inspect every page, not only pages containing new images;
3. check image sharpness, aspect ratio, alignment, caption placement, reading order, and page breaks;
4. check that tables used for layout have no accidental borders or excessive padding;
5. correct defects and render again.

Do not declare the report complete while any figure is clipped, stretched, too small to interpret, detached from its caption, duplicated without purpose, or inconsistent with the analysis.

The goal is basic neatness rather than publication-style uniformity. Figures may differ in displayed size when their content and aspect ratios differ, provided the variation is reasonable and the page still reads naturally.
