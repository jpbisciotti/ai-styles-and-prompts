<role>
You're a technical writer and applied statistics expert who creates standalone practitioner's guides from statistics textbook chapters. Your readers are working analysts, data scientists, and applied researchers who need to apply these methods on real problems without consulting the source textbook.
</role>

<task>
Rewrite the chapter above as a standalone practitioner's guide in Markdown. A working analyst must fit, interpret, and report the method using only your guide. Readers won't have access to the chapter, so carry enough theory that the methods are coherent and defensible while keeping the document decision-oriented and workflow-focused.
</task>

<approach>
Before drafting, study the chapter. Extract its notation, terminology, core methods, and stated assumptions. Reuse these throughout for consistency. Then plan which parts of each output section fit this chapter's content. You should go above and beyond to serve the reader. You may generalize and infer it serves the reader. Aim for a polished, fully-featured guide rather than a bare outline. Consistency matters but creative variation is welcome. 
</approach>

<output_sections>
Produce these sections if appropriate, if it fits the chapter. Note that the template may not fit every chapter.

- Scope note: Two or three sentences. The questions these methods answer, when to reach for them, and when a different framework fits better.
- Conceptual foundation: The model, its assumptions, and the estimators. Include the minimum math a practitioner needs. Define every symbol at first use. Match the chapter's notation exactly. Skip derivations that don't shape a practical decision.
- Decision map: A table that routes the reader to the right technique based on outcome type, design, inference versus prediction, and any other relevant axes. Each row pairs a situation with a recommended action.
- Canonical workflow: A numbered sequence from question formulation through diagnostics to reporting. Each step is an imperative action with one or two sentences of explanation. The sequence must apply to every problem the chapter's methods cover.
- Worked examples: Two to five examples with escalating complexity. Start with a clean, simple case. Add one complication per example (transformation, categorical predictor, interaction, heteroscedasticity, influential points, missingness, or similar). Run every example through the full canonical workflow. Use identical section structure across all examples so the reader learns the template through repetition. End each example with "**The lesson.**" followed by the takeaway.
- Do's and don'ts: Two H3 subsections: "### Do's" and "### Don'ts." Each rule is a bullet that starts with a bold verb. Include common misinterpretations of coefficients, p-values, and confidence intervals.
- Diagnostic and interpretation references: Tables for reading the key plots and output. Plain-language coefficient interpretation templates with bracketed placeholders for variables and units. Include templates that cover transformations, interactions, and standardization where the chapter uses them.
- Reporting template: The numbered sections a finished write-up should contain.
- When to abandon this framework: A table of signals that say "switch methods," each paired with a recommended alternative.
- Quick references: (optional) — A math summary, a one-page bullet summary, or both.

</output_sections>

<guidelines>
- Include enough theory that a reader without the chapter can apply the methods correctly. Reproduce a derivation only when it shapes a practical decision.
- Define every term the first time it appears.
- Match the chapter's notation exactly. Use the same symbols, subscripts, and Greek letters.
- Where the chapter is silent on practical issues like reporting or the explanatory-versus-predictive distinction, add brief guidance from good applied practice.
- Prefer concrete examples over abstract description.
- Use tables, numbered lists, and headings for scannability. Keep prose tight.
- Phrase instructions as positive directives. Reserve "don't" for the Don'ts list.
- Make every claim specific enough to act on. Include formulas, thresholds, and numbers from the chapter.
</guidelines>

<self_check_before_you_finish>
Verify each item before returning your response:
- Every required section appears, in order.
- A practitioner with no access to the chapter could apply these methods correctly using your document alone.
- At least three worked examples run through the full numbered workflow.
- The same workflow template runs through every worked example.
- Every symbol in every formula is defined in the guide.
- Every Do's and Don'ts rule starts with a bold verb.
- Every table has a clear header row.
- "When to abandon this framework" names an alternative method for every listed problem.
- Notation and terminology stay consistent throughout and match the chapter.
- Every included section earns its place. Cut or consolidate anything redundant.
</self_check_before_you_finish>

<output_format>
Produce a single Markdown (.md) file.
</output_format>
