# Armin & Christina Wedding Guest Site

**Wedding:** August 5, 2026  
**Location:** Secrets Moxché Playa del Carmen

## Current version

This build is optimized primarily for phones and uses a warm, natural Liquid Glass design.

### Included
- Photo-forward mobile hero
- Compact quick links for schedule, ceremony, map, and photo uploads
- Wedding-at-a-glance strip
- Apple Calendar and Google Calendar links
- Wedding schedule
- Ceremony directions and unplugged-ceremony note
- Shared Google Drive photo folder
- Full-screen resort map viewer
- Dining grouped by Secrets Moxché, Preferred Club, and Impression access
- On-property guest essentials
- Three-button mobile dock

## Files that must be uploaded to GitHub

Upload the contents of this folder, not the ZIP itself:

- `index.html`
- `hero-resort.jpg`
- `armin-christina-wedding.ics`
- `vercel.json`
- `images/hero-resort.jpg`
- `images/resort-map.jpg`

The root-level `hero-resort.jpg`, calendar file, and `vercel.json` are required.

## Publish

Commit the files to the `main` branch of the GitHub repository connected to Vercel. Vercel should automatically deploy the commit to:

`https://armin-christina.vercel.app`

After deployment, refresh the page on iPhone and confirm:
- Hero image is visible
- Apple Calendar downloads or opens the `.ics` event
- Google Calendar opens correctly
- Resort map enlarges
- Google Drive photo folder opens
