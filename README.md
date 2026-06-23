# Ventura County GIS Web

## Purpose

This repository contains the source code for the Ventura County GIS web landing page and related public-facing GIS website prototypes.

The project was created as both a Ventura County GIS web landing page project and a GitHub Pages learning project. It is intended to document a simple local-to-GitHub workflow while providing a starting point for a public GIS website.

## Repository Information

| Item | Value |
| --- | --- |
| Repository | `vc_gis_web` |
| Organization | `ITSD-VenCo-GIS` |
| Platform | `GitHub` |
| Website Type | `Static HTML` |
| Hosting | `GitHub Pages` |
| Primary File | `index.html` |

Local folder:

```text
D:\vc_projects\00_active_projects\github\vc_gis_web
```

The repository was originally created from a local folder containing a basic `index.html` file and then pushed to GitHub.

## Current Architecture

The current site is intentionally simple and uses a single-page static HTML approach. The main website content is contained in `index.html`.

```text
vc_gis_web/
├── index.html
├── README.md
└── .git/
```

The `.git/` folder is hidden by default and stores Git repository history and configuration. It should not be manually edited.

Future versions may add more HTML files, CSS, JavaScript, application catalogs, GIS service directories, or links to Ventura County GIS applications.

## GitHub Pages Configuration

The site is intended to be hosted with GitHub Pages using the following configuration:

```text
Settings
  → Pages
      → Build and Deployment
          Source: Deploy from a Branch
          Branch: main
          Folder: /root
```

Expected GitHub Pages URL:

```text
https://ITSD-VenCo-GIS.github.io/vc_gis_web/
```

## Local Development

Open the repository folder in VS Code:

```bash
code .
```

For local preview, open `index.html` directly in a web browser. Because the current site is static HTML, no local web server is required for basic editing and preview.

## Git Workflow

Use the normal Git workflow when making updates:

```bash
git status
git add .
git commit -m "Describe update"
git push
```

To check repository information:

```bash
git remote -v
gh repo view
gh repo view --web
```

## Notes

This repository was created to learn and document:

- Git repositories
- GitHub organizations
- GitHub Pages
- VS Code integration
- Local-to-GitHub deployment workflow

## Next Steps

Possible future improvements include:

- Ventura County GIS landing page refinement
- Application catalog
- Open Data links
- Experience Builder application directory
- GIS services directory
- Contact section
- Search functionality
- GIS project portfolio
- Department application showcase

## Revision History

### Initial Setup

- Local folder created
- Git repository initialized
- Repository pushed to GitHub
- GitHub Pages configured
- Initial landing page created
- README created

Created: June 2026
