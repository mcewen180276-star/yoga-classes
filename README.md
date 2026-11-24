# Yoga Companion Library — easy publishing

1. Create a public GitHub repository and upload the CONTENTS of this ZIP (including `index.html` and the `classes` folder).
2. In GitHub Settings → Pages, select Deploy from a branch → main → /(root), then Save.
3. Open Class Builder V2.9, create or load a Yoga class, then press **Export Class for Shared Library (JSON)**.
4. On GitHub, open the `classes` folder → Add file → Upload files. Upload the downloaded `.json` file and commit.
5. Open or refresh your GitHub Pages website. The new class appears automatically. You do NOT need to edit `manifest.json`.

Keep using **Create Client Mini App (HTML)** when you want to send a single class as its own standalone file.

Note: GitHub Pages may take a few minutes to update. Automatic discovery uses GitHub's public repository API, which can be rate-limited. If GitHub's API is unavailable, the library falls back to the optional `classes/manifest.json` list. The repository must be public. Class JSON filenames should contain only letters, numbers, underscores and hyphens.
