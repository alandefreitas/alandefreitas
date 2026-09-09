# Redirect only

This branch no longer holds the website. It serves a redirect from the old address, `https://alandefreitas.github.io/alandefreitas/`, to the site's current home:

**https://alandefreitas.github.io/** (source: [alandefreitas/alandefreitas.github.io](https://github.com/alandefreitas/alandefreitas.github.io))

- `index.html` sends the old root to the new site.
- `404.html` sends any other old path (for example `/alandefreitas/cv`) to the same path on the new host, so old links and bookmarks keep working.
- `.nojekyll` makes GitHub Pages serve these files as they are.

The `master` branch of this repository holds the GitHub profile README and nothing else.
