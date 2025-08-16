# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based personal academic website for Yazeed Alaudah. The site includes:
- Personal portfolio with publications, news, and about page
- Blog functionality with pagination
- Contact form integration via Formspree
- Compass/SCSS for styling

## Development Commands

### Local Development
```bash
jekyll serve
# Serves the site locally at http://localhost:4000
# Jekyll will watch for changes and rebuild automatically
```

### CSS Compilation
```bash
compass compile
# Compiles SCSS files to CSS using the config.rb settings
# Source: assets/scss/ → Output: assets/css/
```

### Build for Production
```bash
jekyll build
# Generates static site in _site/ directory for deployment
```

## Architecture

### Jekyll Structure
- `_config.yml` - Main Jekyll configuration with site metadata and navigation
- `_layouts/` - HTML templates (default.html for main layout, post.html for blog posts)  
- `_includes/` - Reusable HTML components (header, footer, head, scripts, analytics)
- `_posts/` - Blog posts in Markdown format with YAML front matter
- `_site/` - Generated static site (ignore when editing)

### Styling System
- Uses Compass with SCSS preprocessing
- `config.rb` configures Compass compilation settings
- `assets/scss/` contains source SCSS files organized in modules and partials
- Outputs compressed CSS to `assets/css/`

### Content Pages
- `index.html` - Homepage with recent posts pagination
- `aboutme.md`, `news.md`, `publications.md`, `articles.md` - Main content pages
- All pages use Jekyll's front matter and Liquid templating

## Configuration Notes

- Site uses Jekyll gems: jekyll-paginate, jemoji
- Google Analytics 4 integration via include
- Navigation configured in `_config.yml`
- Pagination set to 6 posts per page
- Permalink structure: `blog/:title/`