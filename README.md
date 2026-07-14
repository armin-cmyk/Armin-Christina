# Armin & Christina Wedding Guest Site

Updated liquid-glass wedding guest website for August 5, 2026 at Secrets Moxché Playa del Carmen.

## Important deployment note

Upload **all root files** to the GitHub repository, especially:

- `index.html`
- `armin-christina-wedding.ics`
- `vercel.json`

The previous `vercel.json` redirected every request to `index.html`, which prevented the hero image and calendar file from loading correctly. The hero is now embedded directly inside `index.html`, and the new Vercel configuration serves the `.ics` file with the correct calendar content type.

## Apple Calendar

On iPhone, tap **Add to Apple Calendar**, then open the downloaded `.ics` file and choose **Add All**.

## Photo folder

The site links to the shared Google Drive folder:
`https://drive.google.com/drive/folders/1gBfI49IfP3SRYebnDlKCpT4Dv-A0Dkrv?usp=share_link`
