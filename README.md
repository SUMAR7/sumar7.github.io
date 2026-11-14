# www.sumartech.com

The Sumar Tech website, served by GitHub Pages on the custom domain www.sumartech.com (see `CNAME`).
Old `sumar7.github.io/...` links redirect to the same path on the new domain.

| Path | What it is |
| --- | --- |
| `index.html` | Company home page (SaaS, games, apps, open source). **Not** the games list. |
| `studio/index.html` | The games and apps list. **Add new game cards here**, under "Our games". |
| `legal/index.html` | Every privacy policy and terms page. Add a new game's policy link here too. |
| `<game>/` | A game's own page and `privacy.html` (bloomfall, crowndrop, dabby, naughtypaws, skyport, …). |
| `lanewise/` | The LaneWise web app (built from the pass-lane repo, don't edit by hand). |
| `app-ads.txt`, `sitemap.xml`, `robots.txt` | Keep at the root. Add new pages to `sitemap.xml` with https://www.sumartech.com URLs. |

Rules for the home page: no game or app counts (they go stale), no pricing promises, lead with quality.
Use `https://www.sumartech.com/...` for canonical, og and sitemap URLs, not sumar7.github.io.
Some files use CRLF line endings; keep them that way. Pull before you push.
