OUT OF IDEAS HOME: WEBSITE  (home.outofideas.org)
==================================================

WHAT'S IN THIS FOLDER
  index.html   The whole website: one page.
  images/      Put your before-and-after photos here.

PUT IT ONLINE
  Upload index.html and the images folder to the web root for
  home.outofideas.org, keeping the same folder layout. Any static
  host works (your web host's file manager, Netlify, Cloudflare Pages,
  GitHub Pages). No database or server code is needed.

ADD A JOB TO THE PORTFOLIO
  1. Copy your photos into images/. Use short names with no spaces,
     e.g. deck-rail-before.jpg and deck-rail-after.jpg.
  2. Open index.html in a text editor (Notepad, TextEdit in plain-text
     mode, or VS Code) and find "YOUR PORTFOLIO".
  3. Copy one { ... } block, paste it at the top of the list, and edit it:

     {
       title: "Deck railing tightened",
       category: "Carpentry",
       location: "Sterling",
       date: "2026-11",
       description: "Loose posts re-anchored with new lag bolts.",
       before: "images/deck-rail-before.jpg",
       after:  "images/deck-rail-after.jpg"
     },

     Keep the quotes and the comma after the closing } exactly as shown.
     No "before" photo? Delete that line and the card shows just "after".
  4. Delete the three EXAMPLE jobs once you have your own.
  5. Save and upload index.html (and the new photos) again.

  Filter buttons are made from the "category" names automatically,
  so spell each category the same way every time.

PHOTO TIPS
  - Take before and after from the same spot, at the same angle.
  - Landscape (sideways) photos fit best. The cards are 4:3.
  - Shrink photos to about 1600 px wide before uploading so the page
    loads fast on phones.
  - Leave clients' faces, house numbers and street signs out of the
    shot, and ask permission before posting a job.

CHANGE PRICES OR TEXT
  Search index.html for the text you want to change (e.g. "$95") and
  type over it. Prices appear in the top section and in the
  services/plans section.

THE QUOTE FORM
  The form opens the visitor's email app with the request filled in,
  addressed to contact@outofideas.org. It needs no server. If you later
  want requests to arrive without the visitor's email app, a form
  service such as Formspree or Netlify Forms can be added.
