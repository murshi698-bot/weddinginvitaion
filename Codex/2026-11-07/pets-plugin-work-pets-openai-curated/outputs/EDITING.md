# Murshi & Asna — editing guide

Open `index.html` in a code editor to change the visible invitation wording, names, captions, and venue text. The ceremony time and venue are currently the editable placeholders “Wedding Time” and “Venue Name.”

Open `script.js` to change the countdown date/time and map URL in the `WEDDING` object. The countdown currently targets 27 December 2026 at 6:00 PM India Standard Time; replace that time with the confirmed wedding time.

Replace the images in `assets/` to use different photos. Keep the same filenames, or update the image paths in `index.html`. Replace `assets/wedding-nasheed.mov` with your preferred audio file using the same filename, or update the `<audio>` source in `index.html`. The music starts only after a visitor taps the Music button, as required by mobile browser playback rules.

For WhatsApp link previews, host the folder on a public website and change `og:image` in `index.html` to the full public URL of `assets/couple-by-the-sea.jpg`. Social platforms need a public absolute image URL to fetch the preview. The site itself is static and can be hosted on any static web host.
