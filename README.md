# Christina & Armin's Wedding — Vercel Public Rebuild

This is the complete dark, modern, mobile-first wedding website rebuilt for a Vercel project that publishes the `public` directory.

## Included in this version

- Dark, clean, borderless design
- Restored sunset resort hero image
- Christina & Armin's Wedding browser title
- C&A favicon and Apple home-screen icon
- Apple Calendar and Google Calendar links
- Hyatt Inclusive Collection app links for iPhone and Android
- Wedding schedule and Sky Rooftop Gazebo directions
- High-resolution resort map links
- Dining access and restaurant information
- All-inclusive resort benefits
- Shared Google Drive photo folder
- All accordion sections closed when the page loads

## Repository structure

The production site is inside:

```text
public/
  index.html
  404.html
  hero-resort.jpg
  favicon.svg
  apple-touch-icon.png
  armin-christina-wedding.ics
  site-version.txt
  images/
    hero-resort.jpg
```

The same essential files are also duplicated at the repository root as a fallback. This makes the package resilient if an older Vercel project setting temporarily serves the repository root instead of `public`.

## Deploy

1. Delete or replace the existing files in the GitHub repository root.
2. Upload the **contents of this unzipped folder**, including the entire `public` folder.
3. Commit directly to the `main` branch.
4. In Vercel, set:
   - Framework Preset: Other
   - Root Directory: blank
   - Build Command: blank
   - Output Directory: `public`
5. Redeploy the newest `main` commit.

## Verify the correct build

Open this URL after deployment:

```text
https://armin-christina.vercel.app/site-version.txt
```

It should say:

```text
Christina & Armin Wedding site — public-rebuild-v1
```

The HTML build marker is:

```text
2026-07-16 public-rebuild-v1
```
