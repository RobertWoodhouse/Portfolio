<!-- bmad:context -->
<!-- Verified 2026-09-29 against 52fe1ff. Managed by bmad-project-context; edits inside this block are replaced on refresh. Keep anything you want preserved outside the markers. -->

## Portfolio-Site

Robert Woodhouse's personal portfolio: hand-written static HTML and CSS, served by GitHub Pages at robwoodhouse.com (`CNAME`) straight from `master`. No build step, package manager, or tests. BMad planning output goes in `_bmad-output/`.

## Where things are

- Homepage is `index.html`; its project cards link to `project-*.html`, all styled by the root `style.css`.
- Edit `project-*.html` for project content, not the older `kickups.html`, `dater.html`, `powerupp.html`, `spaceshooter.html`, `illnamethisgamelater.html` — the homepage no longer links to those.

## Running and verifying

- Pushing to `master` publishes to the live site within about a minute; treat every push as a release.
- Verify changes by checking that every local `href`/`src` matches a tracked file with exact case (`git ls-files`); GitHub Pages is case-sensitive but macOS is not, and `images/` mixes `.png` and `.PNG`.

## Conventions that differ from defaults

- Save project images into `images/` and reference them locally; never hotlink from another site — the M.U.M hero image 404'd when its source site changed.

<!-- /bmad:context -->
