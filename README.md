# My Zine Site

A static website built with [Zine](https://zine-ssg.io) and automatically deployed to GitHub Pages.

## Setup

This site uses Zine, a fast static site generator built with Zig. The site is automatically built and deployed via GitHub Actions on every push to the main branch.

## Local Development

1. Install Zig (0.13.0 or later)
2. Clone this repository
3. Run `zig build` to build the site
4. The generated site will be in `zig-out/`

## Project Structure

- `content/` - Markdown content files
- `layouts/` - HTML templates
- `assets/` - Static assets (images, CSS, JS)
- `build.zig` - Zine build configuration
- `.github/workflows/deploy.yml` - GitHub Actions workflow

## GitHub Pages Setup

To enable GitHub Pages for this repository:

1. Go to Settings > Pages
2. Under "Source", select "GitHub Actions"
3. Push to main branch to trigger deployment

The workflow will automatically build and deploy your site without committing any generated files to git.
