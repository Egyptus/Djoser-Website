# Djoser website

**<https://djoser.egyptustech.com/>**

The one-page guide to [Djoser](https://github.com/Egyptus/Djoser), the Windows home for PHP and Laravel. It is a single static `index.html` with no build step.

| File | What it is |
|---|---|
| `index.html` | The whole site: HTML, inline CSS and a little JavaScript |
| `sitemap.xml` | The one URL and the date it last changed |
| `robots.txt` | Allows every crawler and points to the sitemap |

To preview it, open `index.html` in a browser. The only outside file is highlight.js 11.11.1 from cdnjs, pinned with SRI hashes.

When Djoser changes:
- keep the commands, the `djoser.yaml` keys and the agent skill section in step with the public [README](https://github.com/Egyptus/Djoser#readme);
- bump the version in the header badge, the JSON-LD, the install paragraph and the footer;
- update `<lastmod>` in `sitemap.xml`.
