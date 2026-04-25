# emilydev5.github.io — Portfolio Site

Custom portfolio site for [emilyfoster.dev](https://emilyfoster.dev).
Built with Jekyll + Minimal Mistakes (dark skin), hosted on GitHub Pages.

## File Structure

```
emilydev5.github.io/
├── CNAME                     ← tells GitHub to serve this repo at emilyfoster.dev
├── _config.yml               ← Jekyll site settings, theme, author info
├── index.md                  ← main landing page (About, Certs, Projects, Skills)
├── projects.md               ← full project index page
├── _data/
│   └── navigation.yml        ← top nav bar links
├── assets/
│   ├── css/
│   │   └── custom.css        ← colour overrides on top of Minimal Mistakes dark skin
│   └── img/
│       ├── avatar.jpg        ← ADD: your profile photo (400×400px)
│       └── header-bg.jpg     ← ADD (optional): dark banner for home page
└── README-setup.md           ← this file (excluded from Jekyll build)
```

## First-time Setup

1. Create a new GitHub repo named exactly `emilydev5.github.io`
2. Push all files in this folder to the `main` branch
3. Go to Settings → Pages → Source: Deploy from branch → main → / (root) → Save
4. Enter custom domain: `emilyfoster.dev` → Save
5. Tick **Enforce HTTPS** once the certificate is provisioned (~24 hrs after DNS setup)

## Local Preview

```bash
# Install dependencies (once)
gem install bundler jekyll

# Create Gemfile if not present
cat > Gemfile << 'EOF'
source "https://rubygems.org"
gem "github-pages", group: :jekyll_plugins
gem "jekyll-include-cache"
EOF

bundle install

# Serve locally
bundle exec jekyll serve
# Open http://localhost:4000
```

## Adding Content

**New blog post / writeup:**
Create `_posts/YYYY-MM-DD-title-slug.md` with front matter:
```yaml
---
layout: single
title: "Your Post Title"
date: YYYY-MM-DD
categories: [ctf, writeup]
tags: [tryhackme, web, sqli]
author_profile: true
toc: true
---
```

**New project page:**
Create `_projects/project-slug.md` with front matter:
```yaml
---
layout: single
title: "Project Name"
permalink: /projects/project-slug/
author_profile: true
toc: true
---
```

## Updating certifications

Edit the certifications table in `index.md`. Status icons:
- `✅` — Earned
- `🔄` — In Progress  
- `🎯` — Planned
