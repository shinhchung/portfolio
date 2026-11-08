# ShingHong Chung — Portfolio

Professional portfolio focused on data, fintech, networking, and cybersecurity interests. Personal writing stays in the separate `shinhchung.github.io` repository.

## Local preview

```powershell
python -m http.server 4173 --directory site
```

Open http://localhost:4173. This is a dependency-free static website; no build step or API keys are needed.

## Content

- `site/index.html`: introduction, selected work, about, and contact links.
- `site/case-studies/`: project overviews, with limitations stated explicitly.
- `site/styles.css`: responsive shared visual system.

Project descriptions are based on their repository documentation. Quantum Blazar's source remains private. The portfolio features Quantum Blazar and MH Wilds Build Helper, with a public demo link for the latter. English-learning projects and cybersecurity learning notes are not featured. No employment history, certifications, investment returns, or unverified performance numbers are claimed.

## Deploy

GitHub Pages uses GitHub Actions. Push to `main` to upload only `site/` and deploy. Links are relative so the site works under a project subpath. The workflow deployment output and the repository Pages settings show the current canonical URL, which may inherit the account's custom domain.

The blog's DNS, domain, repository, and publishing workflows are managed separately.
