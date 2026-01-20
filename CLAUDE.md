# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build and Development Commands

```bash
# Install dependencies
bundle install

# Run local development server (http://localhost:4000)
bundle exec jekyll serve

# Run with production environment (enables Google Analytics)
JEKYLL_ENV=production bundle exec jekyll serve

# Build site for production
bundle exec jekyll build
```

**Note:** Changes to `_config.yml` require a server restart to take effect.

## Architecture

This is a Jekyll-based personal website hosted on GitHub Pages at www.dianapfeil.com.

**Technology Stack:**
- Jekyll 3.9.3 (via github-pages gem)
- Minima theme (~2.5)
- Kramdown markdown processor
- Google Analytics 4

**Key Directories:**
- `_posts/` - Blog posts in markdown (YYYY-MM-DD-title.md format)
- `_layouts/` - Page templates (home.html shows latest 2 posts)
- `_includes/` - Reusable components (analytics, head, footer, button)
- `assets/css/` - Custom styles (buttons.css)
- `images/` - Site images
- `docs/` - PDFs (thesis, resume, papers)

**Content Pages:** index.md, about.md, blog.md, speaking.md, advising.md, research.md, ai-strategy.md

**Plugins:** jekyll-feed (RSS), jekyll-sitemap, jekyll-seo-tag

**Custom Components:**
- `_includes/button.html` - CTA button component using `{% include button.html button_url="..." button_name="..." button_class="..." %}`
- Google Analytics only loads when `JEKYLL_ENV=production`
