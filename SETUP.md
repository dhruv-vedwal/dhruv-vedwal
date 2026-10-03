# Setup

Create a **public** repository named exactly `dhruv-vedwal`.

Upload these paths through GitHub's website:

- `README.md`
- `assets/hero.gif`
- `assets/hero.png`
- `.github/workflows/profile-visuals.yml`

Then open:

**Settings → Actions → General → Workflow permissions**

Choose:

**Read and write permissions**

Save the setting.

Now open **Actions → Update profile visuals → Run workflow**.

This workflow generates the activity, public-metrics, language and trophy SVGs inside your own repository and commits them back in one run. It no longer uses the failing `language-composition` job or the incompatible trophy-action input that caused your previous run to fail.

The first run should create:

`profile/signal-field-wide-light.svg`  
`profile/signal-field-wide-dark.svg`  
`profile/activity-consistency-wide-light.svg`  
`profile/activity-consistency-wide-dark.svg`  
`profile/language-composition-wide-light.svg`  
`profile/language-composition-wide-dark.svg`  
`assets/trophy.svg`
