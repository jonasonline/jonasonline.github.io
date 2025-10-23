# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static GitHub Pages site for jonasonline.github.io. The site features a split-screen layout with two sections:
- **Work** (left): Links to https://nasman.dev - cybersecurity/development focus
- **Life** (right): Links to https://wineanddine.blog - wine and dining focus

## Architecture

- Single-file static HTML site (`index.html`)
- Split-screen responsive layout (vertical split on desktop, horizontal on mobile)
- Images from Unsplash (free to use)
- Google Fonts: Inter (Work section) and Crimson Text (Life section)
- No build process required - pure HTML/CSS

## Development

### Local Testing
```bash
# Start simple HTTP server
python3 -m http.server 8000

# View at http://localhost:8000
```

### Deployment

GitHub Pages automatically serves `index.html` from the main branch. Changes pushed to `main` are immediately live.

## Design Details

- **Work Section**:
  - Font: Inter (light, sans-serif, modern)
  - Background: Code on laptop screen
  - Link: https://nasman.dev

- **Life Section**:
  - Font: Crimson Text (italic, serif, elegant)
  - Background: Wine and cheese
  - Link: https://wineanddine.blog

- **Colors**: Off-white text (#F5F5DC) with drop shadows for readability
- **Interactions**: Hover effects scale text and images slightly
