# TUNIGHT website

Static website (no WordPress needed). 5 pages: index, menu, banquet, about, reserve.
All CSS and JavaScript are inside each HTML file, so there are no folders to upload.

## Before going live
1. **Opening hours**: open any HTML file, search for `var HOURS=null` and set e.g. `var HOURS={open:"12:00",close:"23:00"}`
   (repeat in all 5 files, or ask your developer to rebuild). With hours set, the site shows "Open now / Closed now".
2. **Photos**: the venue photos load from `https://tunight.in/wp-content/uploads/2026/10/...`.
   If you remove WordPress from tunight.in, download those images first, upload them next to these files
   and replace the URLs, otherwise the photos will disappear.
3. **Vegetarian**: the site describes the kitchen as vegetarian (based on the menu and guest reviews). Change it if that's not right.
4. Menu shows the 6 dishes and prices from the current site. Add more dishes in the same format.

## Upload
Upload all files to the root of tunight.in (or to Vercel / Netlify / GitHub Pages).
