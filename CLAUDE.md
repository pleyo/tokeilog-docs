# Claude Guidelines for TokeiLog Documentation

## Build Commands
- `bundle install` - Install dependencies
- `bundle exec jekyll serve` - Run local development server
- `bundle exec jekyll build` - Build static site to _site directory
- `bundle update github-pages` - Update GitHub Pages dependencies

## Linting
- `markdownlint *.md` - Lint markdown files
- `yamllint _config.yml` - Lint YAML configuration
- `bundle exec jekyll doctor` - Check for common Jekyll errors

## Repository Structure
- Root directory contains main Markdown documents (README.md, PRIVACY_POLICY.md, etc.)
- `_config.yml` - Jekyll configuration file
- GitHub Pages uses Jekyll to build the site from Markdown files

## Style Guidelines
- Use Markdown for all content files
- Follow GitHub Flavored Markdown (GFM) syntax
- Use H1 (#) for document titles
- Use H2 (##) for major sections
- Maintain consistent indentation (2 spaces)
- Use relative links for internal navigation
- Optimize images before adding to repository
- Keep line length under 100 characters

## Naming Conventions
- Use UPPERCASE_WITH_UNDERSCORES for legal document filenames
- Use lowercase-with-hyphens for other Markdown files