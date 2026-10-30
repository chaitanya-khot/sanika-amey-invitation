# Sanika & Amey — Wedding Invitation Website

An animated web version of the video invitation, ready for GitHub Pages.

## What's inside
Everything fits on **one screen with no scrolling**. The layout scales itself to fit any phone, tablet or computer screen.
- **Opening screen**: a marigold wreath seal. Guests tap it, the doors slide apart and the music starts.
- **The invitation**: a marigold toran across the top and garlands down the sides. The couple walks in, then the names are written out by hand. Below them are the parents, the date, muhurtam, reception and venue, plus a live countdown in mini marigold wreaths.
- **View map** (or tap the venue): opens a pop-up with the Google Map and a "Get directions" button.
- **Save the date**: opens a pop-up with Google Calendar and Apple/Outlook buttons.
- **Small corner buttons**: music on/off and replay at bottom-left, share at bottom-right.

## Publish on GitHub Pages
1. Create a new **public** repository on GitHub, e.g. `sanika-amey-wedding`.
2. Upload **everything in this folder**: `index.html`, `.nojekyll` and the `assets/` folder. In the repo, use **Add file → Upload files** and drag in the contents.
3. Open the repo's **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, then pick `main` and `/ (root)`, and click **Save**.
4. After a minute or two the site will be live at
   `https://YOUR-USERNAME.github.io/sanika-amey-wedding/`

## Things to edit (all in `index.html`)
1. **Link preview image**: in the `<head>`, replace `YOUR-USERNAME/YOUR-REPO` in the `og:image` line with your real Pages address. This makes the invitation image show up when the link is shared on WhatsApp.
2. **Invitation text**: edit it directly in the `<!-- Hero -->` section.
3. **Map pin**: the map searches Google for the venue by name. To pin the exact spot, open the venue in Google Maps, tap **Share → Copy link**, and paste that link into `mapsLink` in `CONFIG`.
4. **Music**: replace `assets/music.mp3`. It currently uses the audio from the video, looped.

## Preview locally
Open a terminal in this folder and run `python3 -m http.server`, then visit http://localhost:8000.
Opening `index.html` directly by double-clicking also mostly works.
