# Saili & Jeevan wedding invitation

Static site, no build step.

## Deploy on Vercel
1. Push this folder to GitHub (or run `npx vercel` inside it).
2. Import the repo in Vercel. Framework preset: Other. No build command, no output directory.

## Personalised links
Open `https://YOUR-DOMAIN/links` (the links.html tool), paste guest names (optionally `Name, phone`), and send each personal link on WhatsApp.
A link looks like `https://YOUR-DOMAIN/?to=Rahul%20Sharma` and greets "Rahul Sharma" on the curtain and the invitation.
The plain link with no name greets "Family & Friends".

## Settings (top of the script in index.html)
- `whatsapp`: your number with country code, digits only, to show the RSVP buttons.
- `musicSrc`: path to an mp3 (for example `assets/music.mp3`) that plays when the curtain opens.

## Before sharing
In index.html, change `og:image` to the full address, for example
`https://YOUR-DOMAIN/assets/photo.jpg`, so WhatsApp shows the photo preview.
