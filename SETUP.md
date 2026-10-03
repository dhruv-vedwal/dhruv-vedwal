# GitHub profile setup

Create a **public** repository named exactly `dhruv-vedwal`.

Using GitHub's website, create/upload:
- `README.md`
- `assets/hero.gif`
- `assets/hero.png`
- `.github/workflows/profile-cards.yml`
- `.github/workflows/trophies.yml`

Then go to **Settings → Actions → General → Workflow permissions** and choose **Read and write permissions**.

Open **Actions** and manually run:
- `Update profile cards`
- `Update GitHub trophies`

The README points the hero at the repository's `raw.githubusercontent.com` URL, so the animated GIF is resolved from the repo rather than as a fragile relative path.
