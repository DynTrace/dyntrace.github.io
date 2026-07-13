# Homepage Publication Links Design

## Scope

Update the homepage publication header only. Replace the explanatory summary beneath the author information with `ACM MM 2026` and render it using the same teal-to-blue treatment as the DynTrace wordmark.

Keep the three publication actions on one desktop row in the order arXiv, Code (Coming Soon), BibTex. The Code action is the center item. All three actions use a consistent light surface with the same border, text color, and interaction treatment.

## Layout and Responsive Behavior

The action group becomes a centered flex row. On narrow screens it may wrap without overflow; the requested desktop ordering and centered Code action are preserved whenever all three actions fit on a single row.

## Validation

Check the rendered desktop header for the replacement label, title-matched color, uniformly light buttons, and the Code action in the center position. Confirm the page remains valid HTML and inspect the working tree before committing and pushing the homepage change.
