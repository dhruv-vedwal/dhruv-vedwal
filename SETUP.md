# Setup

Create a **public** repository named exactly `dhruv-vedwal`.

Using only GitHub's website:

1. Upload/create `README.md`.
2. Upload/create `assets/hero.gif`.
3. Upload/create `assets/hero.png` (optional fallback).
4. Create `.github/workflows/profile-visuals.yml` and paste the included workflow.

Then go to:

**Settings → Actions → General → Workflow permissions → Read and write permissions**

Save it, open **Actions**, choose **Update profile visuals**, and click **Run workflow**.

### Why this version

The previous workflow had a separate `language-composition` job that was the failing step. This version removes that job entirely and uses the supported `github-readme-stats-action` for the language card, while the activity card and trophies are generated into the repository itself.

The README therefore references only repository-owned SVGs for the activity, stats, languages and trophies.
