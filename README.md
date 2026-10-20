# Primary Learning App

This repository contains versioned builds of the learning app.

## Current version
The root `index.html` is a small launcher that redirects to the current release.

Current release: **v0.2.2**

## Version folders
- `v0.1.3/` — frozen reference build
- `v0.2/` — frozen v0.2 build
- `v0.2.1/` — frozen responsive iteration
- `v0.2.2/` — current responsive tablet build

Each release keeps its own `index.html`. Older version folders should not be overwritten once frozen.

## Release workflow
1. Create a new version folder, e.g. `v0.3/`.
2. Test that version directly.
3. When approved, update only the root `index.html` launcher to point to the new folder.
4. Record the change in `CHANGELOG.md`.

The app stores learner progress locally in the browser. Keep data-format compatibility in mind when changing saved state in future releases.


## Portfolio demo
The v0.1.3 build is retained as a portfolio/demo version at `/v0.1.3/`. Personal child names have been removed from the public build. The placeholder `[Child Name]` demonstrates where personalisation appears in the interface.

All newer versions use a generic app identity and store child-specific information as user-entered profile data rather than hard-coded names.

- `v0.2.4/` — current release
