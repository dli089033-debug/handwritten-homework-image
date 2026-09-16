# 作业解题与初稿流程

Use this reference when interpreting assignments, solving questions, or planning intentional mistakes.

## 1. Lock the scope

- Extract the teacher's exact requested question numbers.
- Build an explicit ordered list of what will be completed.
- Cross-check every item against the supplied problem material.
- If a question is cut off, illegible, or missing required data, flag it instead of inventing the missing content.

## 2. Build the correct-answer map

Solve every in-scope question first. Keep a private verification map containing:

| Question | Correct answer | Minimum sufficient working | Confidence or issue |
|---|---|---|---|

Use student-appropriate notation. Prefer the shortest reasoning that still makes the answer checkable. Do not copy the full question, add a decorative title, or include unrelated explanations.

## 3. Plan the requested correctness

The correctness rate is based on countable answer units, normally subquestions.

- `100%`: preserve the correct-answer map exactly.
- Named wrong questions: make only those answer units wrong.
- Percentage only: estimate `wrong_count = round(total_units * (1 - target_rate))`, then adjust so the result remains plausible and does not contradict an explicit named list.

Prefer realistic mistake types:

- omitted term or condition;
- sign error;
- arithmetic slip;
- skipped intermediate step that causes a wrong result;
- fraction/common-denominator error;
- incomplete formula use.

Avoid theatrical or obviously deliberate errors. Keep the correct answer available so the red correction can target the actual failing step.

## 4. Compose the black-ink original

- Write from top to bottom as one continuous first attempt.
- Keep subquestions close together and fit the page efficiently.
- Do not leave deliberate gaps for later correction.
- Do not over-polish alignment or typography.
- Use compact labels such as `2.(5)`, `2.(6)`, `3.(1)` followed by the work.

## 5. Plan red corrections

Only use red corrections when an intentional or genuine error exists.

- Mark the incorrect sign, number, term, or step where it occurs.
- Add the corrected form nearby using smaller, slightly crowded red handwriting.
- Do not cover correct black work with decorative red marks.
- At `100%` correctness, omit all red writing.

## 6. Pre-generation review

Before image generation, show the user:

1. Included question numbers.
2. Short correct-answer outline.
3. Planned intentional errors, if any.
4. Planned red corrections, if any.
5. Expected page count.

Generate only after the user confirms, unless they explicitly waived this review.
