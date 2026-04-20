# YouYouGhost Website

This is a simple static site that Codex can edit directly inside the
`YouYouGhost-website` folder.

## Files

- `index.html`: main site page
- `wrangler.toml`: Cloudflare deployment config placeholder

## Codex workflow

Next time, open Codex in this folder and ask for changes in plain English.

Examples:

- "Update the homepage text"
- "Change the background color"
- "Add a contact section"
- "Make the page look more playful"

Codex can read and edit the files in this folder directly.

## GitHub and Cloudflare flow

Recommended setup:

1. Keep this folder as the local source of truth.
2. Connect the folder to a GitHub repository.
3. Connect the GitHub repository to Cloudflare Pages.
4. Push changes to GitHub after edits.
5. Let Cloudflare deploy automatically from GitHub.

## Current project type

This project is a static HTML site, so no build step is required.

Suggested Cloudflare Pages settings:

- Framework preset: `None`
- Build command: leave empty
- Build output directory: `.`

## Notes

If you want, Codex can also help with:

- initializing Git in this folder
- connecting the remote GitHub repository
- committing and pushing changes
- preparing a better multi-file structure with CSS and assets
