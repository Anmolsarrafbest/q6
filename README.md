# Matrix Build Demo (build-8b0c652)

This repository demonstrates a GitHub Actions matrix build that produces and uploads artifacts for multiple variants.

Workflow: `.github/workflows/matrix-build.yml`

Contact: replace-this-with-your-email@example.com

How to run

1. Push these changes to your GitHub repository (branch `main`), or trigger the workflow manually via the Actions tab.

Quick push (PowerShell):

```powershell
git add .
git commit -m "Add matrix build workflow and README"
git push origin main
```

What this workflow does

- Runs a matrix over Node.js versions 14, 16 and 18 (three parallel jobs).
- Each job creates a non-empty artifact file and uploads it using `actions/upload-artifact@v4`.
- Artifacts are named with the prefix `build-8b0c652-...` (for example `build-8b0c652-v14`).

Notes

- Make sure your default branch is named `main` or adjust the workflow trigger accordingly.
- Replace the contact email above with your real address if desired.
