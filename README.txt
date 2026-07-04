FARHANG BAKHSHI - PORTFOLIO SITE
================================

Files (keep them together in one folder):
  index.html                     the portfolio page
  DeterministicMap_embedded.html interactive MILP dashboard (in-page embed + full screen)
  alics.mp4                      ALICS demo video
  alics_poster.jpg               video poster frame

DEPLOY ON GITHUB PAGES (free)
-----------------------------
1. Go to github.com/new and create a PUBLIC repository named exactly:
       farhangbakhs.github.io
2. On the empty repo page click "uploading an existing file",
   drag in ALL four files above, and commit.
3. Wait 1-2 minutes. The site is live at:
       https://farhangbakhs.github.io

LINK-ONLY ACCESS
----------------
index.html contains <meta name="robots" content="noindex, nofollow">,
which tells Google/Bing not to index the site - so people only find it
through the link you give them. To make it publicly discoverable later
(e.g. so recruiters googling your name find it), delete that one line.

UPDATING
--------
Replace any file in the repo and commit; the site updates within a
minute or two.

LOCAL PREVIEW
-------------
From this folder run:  python -m http.server
then open http://localhost:8000
