# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Mintlify documentation site that follows the Project Codex Standard for AI-managed development documentation. The site is built with Mintlify, a modern documentation platform that converts MDX files into a beautiful documentation website.

## Common Development Commands

### Local Development
```bash
# Install Mintlify CLI globally (if not already installed)
npm i -g mint

# Run local development server at http://localhost:3000
mint dev

# Update Mintlify CLI to latest version
mint update
```

### Troubleshooting
- If dev environment isn't running: Run `mint update` to ensure you have the latest CLI version
- If a page loads as 404: Ensure you're running in a folder with a valid `docs.json`

## High-Level Architecture

### Documentation Structure
The documentation is organized into two main tabs defined in `docs.json`:
1. **Guides Tab**: Getting started, customization, content writing, and AI tools documentation
2. **API Reference Tab**: API documentation and endpoint examples

### Key Configuration Files
- **docs.json** - Main configuration file that defines:
  - Navigation structure and tabs
  - Theme colors and branding
  - Logo paths for light/dark modes
  - External links (Documentation, Community, Blog)
  - Contextual options for code blocks (copy, view, ChatGPT, Claude, etc.)

### Content Organization
- **MDX Files**: All documentation content is written in MDX format (Markdown with JSX support)
- **Navigation**: Hierarchical structure with tabs > groups > pages
- **API Documentation**: Uses OpenAPI specification (`api-reference/openapi.json`)
- **Reusable Content**: Snippets stored in `snippets/` directory for DRY documentation

### Project Codex Integration
The repository includes the Project Codex Standard (`project_codex.md`) which defines a comprehensive documentation standard for AI-managed solo development. This standard emphasizes:
- **Cognitive Symbiosis**: Merging human creativity with AI systematization
- **Stateful Knowledge**: Every piece of information exists in a defined lifecycle state
- **The Sacred Manifest**: A single, always-current entry point (`_MANIFEST.md`) that provides complete project orientation

## Important Context from Project Files

### From README.md
- Changes are deployed to production automatically after pushing to the default branch
- Mintlify GitHub app must be installed from the dashboard for automatic deployments
- Local preview available at `http://localhost:3000` when running `mint dev`

### Navigation Structure (from docs.json)
The documentation includes:
- Getting started guides (index, quickstart, development)
- Customization guides (settings, navigation)
- Content writing guides (markdown, code, images, reusable snippets)
- AI tools documentation (Cursor, Claude Code, Windsurf)
- API reference with endpoint examples (GET, CREATE, DELETE, webhook)

## Working with This Codebase

When modifying documentation:
1. Edit MDX files directly for content changes
2. Update `docs.json` for navigation or configuration changes
3. Test changes locally with `mint dev` before committing
4. Ensure all links and references are valid
5. Follow the existing MDX formatting patterns