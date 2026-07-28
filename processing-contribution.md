# My Contributions to the Processing Organization

Contributions span 2 repositories under the `processing` org: **p5.js** and **p5.js-website**.

---

## Repo: `processing/p5.js`

### Pull Requests

- [#8998 - Fix static p5 vector method](https://github.com/processing/p5.js/pull/8998) — Open PR fixing a bug in a static `p5.Vector` method.
- [#8983 - Added typo benchmark test for textToPaths()](https://github.com/processing/p5.js/pull/8983) — Open PR adding a typography-related benchmark test for the `textToPaths()` function.

### PRs Reviewed

- [#9014 - Fixes #9000 (by NalinDalal)](https://github.com/processing/p5.js/pull/9014) — Reviewed this PR and left performance-focused feedback: suggested using a fast-path key check instead of `maxes.join(',')` (which allocates a new string on every call inside loops), and recommended checking `this._color.space.id === 'srgb'` instead of `this.mode === RGB` so the fast path works for any color object backed by sRGB.

---

## Repo: `processing/p5.js-website`

### Pull Requests

- [#1533 - Add Hindi translation for Teachers Guide to p5.js v2](https://github.com/processing/p5.js-website/pull/1533) — Open PR adding a Hindi translation of the "Teachers Guide to p5.js v2" documentation.
- [#1520 - Fix 404 on localized library directory page](https://github.com/processing/p5.js-website/pull/1520) — Merged PR fixing a 404 error occurring on the localized library directory page.

