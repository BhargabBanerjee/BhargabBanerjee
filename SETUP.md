# Bhargab Banerjee — GitHub Profile Pack

## Contents
- `README.md` — profile README
- `assets/hero-banner.png` — custom neon purple/cyan hero banner
- `assets/profile.png` — supplied profile photo
- `assets/footer.svg` — custom footer graphic

## Install
1. Open the repository `https://github.com/BhargabBanerjee/BhargabBanerjee`.
2. Extract this ZIP.
3. Upload `README.md` and the complete `assets` folder to the repository root.
4. Commit to the `main` branch.
5. Refresh `https://github.com/BhargabBanerjee`.

The README uses relative paths for local assets, so keep the `assets` folder next to `README.md`.

## Git commands
```bash
git add README.md assets
git commit -m "Redesign GitHub profile portfolio"
git push origin main
```

## Notes
- Live cards (stats, streak, activity graph, trophies, typing SVG and skill icons) depend on external services.
- GitHub profile counts shown in the static snapshot section were checked on 6 November 2026; replace them as your profile changes or remove that section if you prefer only live widgets.
- The GitHub profile README cannot run JavaScript or custom CSS. This design uses GitHub-supported Markdown/HTML and embedded images.

## GitHub telemetry
- Stats cards use GitHub Stats Extended, the maintained successor-compatible endpoint.
- The activity graph uses the project's current canonical `github-readme-activity-graph.vercel.app` deployment.
- Trophy cards were removed because the former public trophy deployment is disabled; live Shields badges now show repository, follower and star counts using GitHub's public API.
- If a third-party image host is temporarily unavailable, the README content and locally hosted banner/profile/footer remain unaffected.

## One-time setup for the contribution animation
1. Upload the included `.github/workflows/snake.yml` file to the profile repository.
2. In GitHub, open **Settings → Actions → General → Workflow permissions**.
3. Ensure workflows have permission to read and write repository contents.
4. Open **Actions → Generate contribution snake → Run workflow**.
5. After it completes, GitHub Actions creates/updates the `output` branch. The README animation then loads from that branch.
