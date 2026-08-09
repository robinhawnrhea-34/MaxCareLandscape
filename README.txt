MAX CARE LANDSCAPING - WEBSITE
==============================

WHAT'S INCLUDED
  index.html ................ the complete website (one file)
  assets/hero.mp4 ........... drone background video (720p, web-optimized)
  assets/hero-poster.jpg .... still frame shown before the video plays
  assets/logo-white.png ..... transparent white logo (for dark backgrounds)
  assets/logo-green.png ..... transparent green logo (for light backgrounds)
  assets/*-fullres.png ...... your original high-res logos, for other uses

HOW TO PREVIEW
  Double-click index.html to open it in any web browser. Keep the
  index.html file and the assets folder together in the same place.

HOW TO PUBLISH IT
  Upload index.html and the assets folder to any web host. Easy options:
  Netlify (drag the whole folder onto app.netlify.com), Vercel, GitHub
  Pages, or your existing hosting/cPanel. The structure must stay the same.

QUICK EDITS (open index.html in any text editor)
  1) YOUR CONTACT DETAILS
     Near the bottom, find the block that starts with "const CONFIG".
     Update phone, phoneTel (digits only), email, area, and hours.
     Every place these appear on the site updates automatically.

  2) MAKING THE FORMS EMAIL YOU
     By default the forms show a success message but do not send anywhere.
     To receive real submissions, create a free form endpoint at
     https://formspree.io , then paste your endpoint URL into
     FORM_ENDPOINT inside the CONFIG block. Both the estimate request and
     the review form will then be delivered to your inbox.

  3) REPLACING THE SAMPLE REVIEWS
     Find "const SEED_REVIEWS". Edit the name, project, text, and rating
     for each, or add/remove entries. These are placeholders until you
     drop in your real reviews.

  4) SWAPPING THE VIDEO
     Replace assets/hero.mp4 with your own clip (keep the same filename),
     and optionally replace assets/hero-poster.jpg with a matching frame.

NOTES
  - The video is muted and loops, which is required for autoplay in
    browsers. A full-quality 1080p version can be re-exported from your
    original footage if you ever want it.
  - Colors and fonts follow the Max Care brand green with a warm gold
    accent, Spectral and Figtree typefaces (loaded from Google Fonts).
