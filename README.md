# NEON POP — official site

Landing page for the NEON POP mobile game, served by GitHub Pages at
<https://wish-go.github.io/neon-pop/>.

This URL is registered in the Google Play Console store listing ("Website"),
so **do not rename this repository** — GitHub Pages does not redirect after a
rename and the store link would 404.

Legal pages live in a separate repository, `neonpop-legal`, because their URLs
are compiled into the shipped app binary (`PloxLinks.LEGAL_BASE`) and cannot
move at all:

- <https://wish-go.github.io/neonpop-legal/privacy.html>
- <https://wish-go.github.io/neonpop-legal/terms.html>

Single static page, no build step. Edit `index.html` and push.
