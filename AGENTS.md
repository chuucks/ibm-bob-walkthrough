# AGENTS.md

This file provides guidance to agents when working with code in this repository.

## Non-Obvious Project Facts

* **Single-Page Architecture**: This project contains no routers or multi-page routing. All content partitions are housed within `index.html` as standard `div` blocks carrying the class `.slide-page`. 
* **Tab-State Switching**: Slide transitions are driven entirely by toggling the `.active` CSS display class. Switching slides automatically triggers a smooth scrolling action to the top of the browser viewport.
* **Side-Navigation Name Mapping**: The sidebar mapping matches the navigation link span values:
  * When `pageId` is `'cover'`, the sidebar JavaScript checks if the link span text contains `'home'` (case-insensitive) to highlight it as active.
  * Adding new navigation slides requires both matching the `.slide-page` id format (`page-<id>`) and updating the sidebar search text match conditions in `switchPage()`.
* **Theme Styling Rules**: Colors utilize CSS variables linked to the `html[data-theme]` attribute selector. Do not use hardcoded hex values in new stylesheet classes; use standard Carbon token custom variables (e.g. `--interactive`, `--border-color`).
* **Bob Tip Randomizer**: Inside `<script>`, `bobTips` holds an array of authentic, documentation-verified Bob technical tips. Cycling chooses index numbers at random to prevent sequential repetition.
