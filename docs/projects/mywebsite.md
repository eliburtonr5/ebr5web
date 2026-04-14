---
title: My Website
description: How the website is built, stored, and deployed
draft: false
---

# My Website


This site is my portfolio and technical blog. It is built with Material for MkDocs, stored in GitHub, and deployed through Cloudflare Pages so updates go live automatically.

## How it works


The site is generated as a static website from Markdown content and YAML configuration.

- I write content in `docs/` using Markdown files.
- `mkdocs.yml` contains the site settings, theme, navigation, and plugins.
- Material for MkDocs converts the Markdown and YAML into a static HTML website.
- Cloudflare Pages publishes the built site and keeps it in sync with GitHub.


## What each part does

### Markdown


Markdown is used for the page content, headings, lists, images, and links. It is the main way I add documentation, project descriptions, and notes.

### YAML


YAML is the configuration language for MkDocs. It defines:

- site title and description
- navigation structure
- theme settings
- plugins and extensions
- extra files such as icons and assets

### Python / Material for MkDocs


Material for MkDocs is a Python-based static site generator. It reads the Markdown content and YAML config, then builds the site into HTML, CSS, and JavaScript files.

I do not run Python in the browser. Python is only used during the build step to generate the site.


## Repository and deployment

The site source code lives in my GitHub repository [ebr5web](https://github.com/eliburtonr5/ebr5web).

Cloudflare Pages is connected to that repository. When I push changes to the `main` branch, Cloudflare detects the update, rebuilds the site, and publishes the new version automatically.


## Why this stack

I chose this setup because it is:

- easy to maintain with Markdown content
- flexible through YAML configuration
- fast to build as a static site
- automatically deployable from GitHub via Cloudflare


## What I included on the site

The website includes:

- project write-ups
- certifications
- link to code repository
- a clean Material theme with responsive navigation
### **More to come!**

---

Eli Burton - 4/13/2026
