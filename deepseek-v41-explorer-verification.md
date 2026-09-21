# DeepSeek V4.1 Flash — separate implementation explorer

[Open the explorer](https://phi9t.github.io/stratum-pages/deepseek-v41-explorer.html).

This is the supplied standalone explorer, published unchanged. It is separate from
[the existing STRATUM V4.1 chapter](https://phi9t.github.io/stratum-pages/deepseek-v4.1.html).

The supplied source archive rebuilds to identical HTML. Fresh checks on the published bytes:

- 28 model/scene tests and 3 local-server tests passed.
- Chromium 140.0.7339.16: 197 geometry states, 80 module/lens/theme combinations,
  48 memory scenarios and 32 responsive cases.
- Zero detected geometry defects, JavaScript errors or external runtime requests.
- All 8 tour steps, UI interactions, SVG/JSON exports and URL-state checks passed.
- Both portable and source-module loopback HTTP navigation passed.
- Portable HTML privacy scan passed. Existing pages were not replaced.

HTML SHA-256: `ba401562505d5b73af009a18e7ebda60d4d8f56fdba20e9ba4abf6c6ab5dd3f7`.

Scope: website engineering only. The supplied explorer labels its code as explanatory
pseudocode and its numerical toys as illustrations. No checkpoint execution, GPU runtime,
independent scientific certification or other-browser certification is claimed.

Reproduction note: invoke the supplied Python browser/capture tests with `python -P`
or `PYTHONSAFEPATH=1` so `tests/inspect.py` cannot shadow Python's standard-library `inspect`.
