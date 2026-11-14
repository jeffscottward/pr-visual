# pr-visual

Dark before-vs-after graphic at the top of every PR/MR (owner rule 2026-11-14).

- `pr-visual <PR URL> --before ... --after ...` (non-UI) or `--before-url/--after-url` (UI screenshots, 1280 + 375 px). `--mock` adds a MOCK label.
- `pr-visual check <PR URL>`: exit 1 when no image in the first 15 lines.
- GitHub check: copy `.github/workflows/pr-visual.yml` into a repo.
- GitLab check: include `pr-visual-check.yml` from `jeffscottward/ci-config`.
- Report-only until 2026-11-17, enforced after.
