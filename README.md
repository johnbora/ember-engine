# The Ember Engine: the built site

A real-time generative fire for McLean's Hearth, built and published with
GitHub Pages. The source is kept in a private repository; this one holds
only what the browser loads, and each new build replaces it.

Built from commit `2e80382`: milestone 10, with the poster size confirmed.

| Address | What it does |
|---|---|
| `https://johnbora.github.io/ember-engine/` | The fire |
| `…/ember-engine/?bench` | Measure this machine against the performance budget, then **Save report** and send the file back |
| `…/ember-engine/?kiosk` | A showroom wall: no staff panel, capture or readout. Add `&labels=0` for no preset card, `&sound=0` for silence |

To measure a machine: open the `?bench` address in Chrome, press F11 for
full screen, leave it alone until it finishes (usually under a minute),
then click **Save report** and send back the `ember-bench_….json` file.

The interface fonts (Barlow Condensed, IBM Plex Mono, Cormorant Garamond)
are under the SIL Open Font License 1.1; their licence texts are in
`fonts/`.
