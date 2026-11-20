# Djoser website

The one-page site for Djoser at <https://djoser.egyptustech.com/>, with the full guide. It holds the same content as the welcome page Djoser serves offline at `https://djoser.localhost`.

| File | What it is |
|---|---|
| `index.html` | The whole site: HTML, CSS and a little JavaScript, with no build step |
| `robots.txt` | Allows every crawler and points to the sitemap |
| `sitemap.xml` | The one URL, with the date it last changed |

## Preview

Open `index.html` in a browser, or serve the folder:

```powershell
python -m http.server 8080
```

## Outside files

The page loads only highlight.js 11.11.1 from cdnjs, for YAML colouring, pinned with Subresource Integrity hashes. Everything else is inline. Social previews use `assets/overview.webp` from the public Djoser repository.

## When Djoser changes

- Keep the commands and `djoser.yaml` keys in step with the public `README.md`.
- Bump the version in four places: the header badge, the JSON-LD `softwareVersion` and `releaseNotes`, the install paragraph and the footer.
- Update `<lastmod>` in `sitemap.xml`.
