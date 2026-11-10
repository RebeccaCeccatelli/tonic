# Tonic

Front page for the Tonic master's thesis (*Towards Controllable Symbolic Music Generation with Energy-Based
Transformers*, ETH Zürich × MIT Media Lab): showcase, interactive demo, Listening Archive, listening survey,
thesis and code.

Live: https://rebeccaceccatelli.github.io/tonic/

## Updating a link

All links live in the `LINKS` block near the top of `index.html`. Edit it (the GitHub web editor is fine) and
commit; GitHub Pages republishes within a minute.

- **Hosted interactive demo:** `bash demo/launch_demo.sh --share` prints a `https://….gradio.live` URL that
  lives up to 7 days (while the demo keeps running). Put it in `demoHosted` and the launch time in `demoHostedStarted`
  (e.g. `"2026-11-12T14:00:00+01:00"`). The card shows "Live until …" and switches itself off when it expires.
- **Thesis:** put the PDF's URL in `thesisPdf` (for example a release asset of this repo); the "coming soon"
  labels turn into links.
- **Survey:** the card says "Open" and has no closing date (answers are always welcome).
