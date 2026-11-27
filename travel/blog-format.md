# On Foot blog — format

The blog's own README is the authority on how posts are built: https://github.com/gpmdyg9b4z-spec/on-foot-blog#readme. This page only summarises it.

- **Site:** https://gpmdyg9b4z-spec.github.io/on-foot-blog/ (repo `on-foot-blog`, GitHub Pages from `main`)
- **Posts:** `_posts/<slug>.html`. The slug is `<place>-<year>`, e.g. `krakow-jewish-quarter-2026`. Each post carries a `walk-meta` JSON block (date, place code, themes, series, card text) that drives the homepage, filters, "More walks", the sitemap and the RSS feed.
- **Styles:** the shared `assets/post.css`. A post's own `<style>` holds only overrides, such as the header watermark glyph.
- **Writing:** British English. Polished but unstuffy. Follows the walk stop by stop, with story-boxes, key-facts and blockquotes. Disputed claims are flagged.
- **Privacy:** guides, volunteers and members of the public are never named. The tour organisation can be named. Posts never mention recordings or transcripts.
- **Photos:** a 1600px copy in `images/<slug>/`, with 800px and 1200px copies made by the Action. Each links to its Getty Images page, credit `Sergio Amiti / Getty Images`. An optional `card.jpg` (960×640) is used for the homepage card.
- **Two ways in:** upload a finished post, or push notes to `_notes/<slug>.txt` and the Action writes the post with Claude.

Place codes: `london/central|n|nw|e|se|sw|w`, `uk/<county>`, `abroad/<country>`. Themes and series are listed in the blog README.
