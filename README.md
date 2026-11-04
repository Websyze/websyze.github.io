# libre-apps.org

Site of the libre-apps organization: free and open source apps that deliver real value, with no ads and no unnecessary data collection.

Served by GitHub Pages at <https://libre-apps.org>. One static page, no build, no dependencies and no third party requests: `index.html`, `assets/css/site.css` and the images in `assets/img/`. English and Portuguese live side by side in the HTML; the toggle (or `?lang=pt|en`) picks one.

Run it locally:

```bash
python3 -m http.server 8000
```

When `site.css` changes, bump `?v=` in `index.html` so browsers fetch the new file.
