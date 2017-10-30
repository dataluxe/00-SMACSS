##### How did you determine which rules should be placed in each new CSS file?

General SMACSS rules: Single-elements selectors not having layout-type properties go in base, selectors on non-reused elements having to do with layout go in 'layout', selectors styling reusable pieces of the page go in 'modules'.

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

No. All styles were selected in a proper cascading manner with no redundancy.
