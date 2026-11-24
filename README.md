# ColorPop content

Coloring pages that the ColorPop app downloads, so new packs arrive without an app update.

- `catalog.json`: categories and pages (`rev` changes whenever a picture changes)
- `pages/*.png`: line art, 1024 × 1024, transparent background

Do not edit by hand. Everything here is generated from the main app repo with
`tools/publish_content.sh`. Only drawings and the page list live here; the app
never uploads anything.
