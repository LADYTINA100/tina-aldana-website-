# Tina Aldana website starter

A modern, minimal static website starter for Tina Aldana.

## What's included
- `index.html` — homepage content
- `styles.css` — responsive design
- `admin/config.yml` — starter configuration for a visual content editor (requires additional authentication setup)

## Publish with Netlify
1. Create a new **public or private GitHub repository** named `tina-aldana-website`.
2. Upload `index.html`, `styles.css`, `README.md`, and the `admin` folder to the repository's root.
3. In Netlify, choose **Add new site → Import an existing project**, select GitHub, and choose `tina-aldana-website`.
4. Leave the build command blank and the publish directory as `.` (a single period), then deploy.
5. Netlify will give you a temporary `*.netlify.app` URL to test.

## Before launch
- Replace the sample email address in `index.html`.
- Replace the music/video placeholder links with real links.
- Add an approved artist photo. The hero is currently a stylized placeholder, not a real photo.
- Add a Google Calendar embed for shows if you want to update events visually from Google Calendar.

## Domain
Do not change Namecheap DNS until the site is deployed and the Netlify domain settings show the records to use. Then add the custom domain in Netlify and follow its current DNS instructions.

## Visual editing note
The `admin/config.yml` file is only a starter. A CMS editor needs authentication configured before it will work. For the simplest gig updates, a dedicated Google Calendar embedded on the Shows page is recommended; adding/editing events in Google Calendar will update the calendar shown on the site.
