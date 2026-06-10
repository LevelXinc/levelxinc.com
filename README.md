# Level X — studio website

Static site built with Jekyll, hosted on GitHub Pages, served at levelxinc.com.

## Run locally
    bundle install
    bundle exec jekyll serve
Then open http://localhost:4000

## Publish a blog post
Add a Markdown file to `_posts/` named `YYYY-MM-DD-title.md` with front matter:

    ---
    layout: post
    title: "Your title"
    date: 2026-06-10 09:00:00 +0000
    tags: [mindfulness, families]
    description: "One-sentence summary used for SEO, AI search, and the listing."
    ---

    Your content in Markdown...

Commit and push — GitHub Pages rebuilds automatically.

## Notes
- `CNAME` binds the site to levelxinc.com.
- `sitemap.xml` and `feed.xml` are generated automatically (jekyll-sitemap, jekyll-feed).
- SEO meta + Open Graph come from jekyll-seo-tag; per-page `title`/`description` drive them.
- Add a real `og-image.png` (1200x630) at the repo root for link-preview images.
