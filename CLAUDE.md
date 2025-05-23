# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Project Xanadu documentation site built with MkDocs Material. It explores Ted Nelson's hypertext vision through conceptual documentation about bidirectional links, transclusion, and advanced hypertext systems.

## Documentation Development Commands

```bash
# Install dependencies
pip install -r requirements.txt

# Start local development server
mkdocs serve

# Build static site
mkdocs build

# Deploy to GitHub Pages (if configured)
mkdocs gh-deploy
```

## Project Structure

- `docs/` - Main documentation content in Markdown
- `mkdocs.yml` - MkDocs configuration with Material theme
- `project_xanadu.md` - Narrative story about Project Xanadu's history
- `requirements.txt` - Python dependencies for MkDocs

## Architecture

This is a static documentation site using:
- **MkDocs** with Material theme for documentation generation
- **Markdown files** in `docs/` directory for content
- **GitHub Pages** deployment (https://rasinj.github.io/Xan/)

The documentation covers conceptual aspects of Ted Nelson's Xanadu hypertext system including bidirectional links, transclusion, and content addressing - primarily educational/theoretical content rather than working implementation.

## Content Guidelines

Documentation follows MkDocs Material conventions with:
- Admonition blocks for callouts (`!!! info`, `!!! warning`)
- Code highlighting with `pymdownx.highlight`
- Navigation structured by concepts and implementation details
- Some placeholder Lorem Ipsum content mixed with actual Xanadu concepts