> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "microfeed instance" not "site" or "installation"
- Use "feed" not "channel" when referring to the published content
- Use "admin dashboard" not just "dashboard"
- Use "Cloudflare Pages" not just "Pages"

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Focus on user-facing features and workflows
- Document both the admin dashboard and public-facing feeds
- Include API documentation for developers using microfeed as a headless CMS
- Cover deployment and configuration on Cloudflare
