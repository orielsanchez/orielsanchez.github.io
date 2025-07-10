# somesoftwaredev

Personal blog built with [Hugo](https://gohugo.io/) using the [Archie](https://github.com/athul/archie) theme.

## Site

Live at: [https://orielsanchez.github.io](https://orielsanchez.github.io)

## Development

### Prerequisites
- [Hugo](https://gohugo.io/installation/) (extended version)

### Local Development
```bash
# Clone the repository
git clone https://github.com/orielsanchez/orielsanchez.github.io.git
cd orielsanchez.github.io

# Initialize submodules (for theme)
git submodule update --init --recursive

# Start development server
hugo server -D

# View at http://localhost:1313
```

### Adding New Posts
```bash
# Create new post
hugo new posts/your-post-name.md

# Edit the post in content/posts/your-post-name.md
# Set draft = false when ready to publish
```

### Deployment
The site automatically deploys to GitHub Pages via GitHub Actions when changes are pushed to the main branch.

## Content Structure
```
content/
├── about.md          # About page
└── posts/           # Blog posts
    └── *.md         # Individual posts
```

## Theme
Using the [Archie theme](https://github.com/athul/archie) - a minimal, clean Hugo theme.

---

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/orielsanchez)