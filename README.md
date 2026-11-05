# strava-map-redirect

Redirects the old site, `strava-map.jakas.si`, to
[Activity Atlas](https://activity-atlas.jakas.si/) (previously "Strava on Maps").

`index.html` and `404.html` are the same page: every path on the old domain
lands on the new one with its path, query and hash kept, so deep links such as
`#analytics` still open the right view. GitHub Pages serves this repo's `main`
branch, with `strava-map.jakas.si` as its custom domain.
