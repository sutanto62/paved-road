# The Paved Road: Terminal Edition

🔗 **Live demo:** https://sutanto62.github.io/paved-road/

An interactive, terminal-styled simulator exploring the tradeoffs of Platform Engineering's "paved road" — the idea that teams move fastest when the easy path is also the safe path. Single static HTML page, no build step, no dependencies beyond a Google Font.

## What it covers

| Tab | Explores |
|---|---|
| `1` configuration | Golden path, guardrail, safety net, and checkpoint controls — plus environment, rollback timing, and fail-open vs. fail-closed behavior |
| `2` go off road | What happens when a team deviates from the paved road |
| `3` who owns the pager | On-call ownership tradeoffs between platform and product teams |
| `4` say no | When and how platform teams should push back on requests |
| `5` cage meter | Measuring whether guardrails have become a "golden cage" |

## Run locally

It's a single HTML file — just open it:

```bash
open index.html
```

Or serve it:

```bash
python3 -m http.server 8000
```

## Deployment

Served via GitHub Pages from the `main` branch root. Any push to `main` updates the live site.

## License

MIT — see [LICENSE](LICENSE).
