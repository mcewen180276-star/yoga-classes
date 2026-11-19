# Yoga Companion Class Library — GitHub Pages

1. Create a new **public** GitHub repository (e.g. `yoga-companion-library`).
2. Upload `index.html`, the `classes` folder, and its `manifest.json` file to the repository root.
3. In repository Settings → Pages, select **Deploy from a branch**, branch **main**, folder **/(root)**.
4. Open your Pages URL once published. The catalogue will display all JSON files listed in the manifest.

## Publish your own classes

In Yoga Class Builder V2.8 or Fitness Master Hub V17.5, open/create a class and click **Export Class for Shared Library (JSON)**. Download the `.json` file. Upload it to the `classes/` folder in the GitHub repository. Edit `classes/manifest.json` to add the filename, for example:

```json
{
  "classes": [
    {"file":"my-hatha-class.json","category":"Hatha","description":"Gentle full-body session"},
    {"file":"yoga-for-runners.json","category":"Sport-specific"}
  ]
}
```

Commit changes. Refresh the published page to see new classes. Removing a file from the manifest hides it from the catalogue. Keep names exact, including capitalisation.

The catalogue does **not** automatically discover files uploaded to GitHub: you must update the manifest. You can still send individual mini-app HTML files using the separate **Create Client Mini App (HTML)** button.

The website is public to anyone with the URL. Only upload classes you intend to share. Classes are not saved back to GitHub by visitors. Personal music files are selected locally on each visitor's device.

For local testing without GitHub, open `index.html` and use **Open a class JSON file**. Published-class loading requires an HTTP(S) server, such as GitHub Pages.
