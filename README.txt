COASTAL KARNATAKA EXPLORER — COURSERA PROJECT FILES

Files
-----
index.html  Ready-to-host interactive webpage. Open it in a browser to preview.
index.Rmd   R Markdown source using the R leaflet package to produce the map.

Project title for Coursera
--------------------------
Coastal Karnataka Explorer — Udupi & Manipal

Suggested Title field
---------------------
Coastal Karnataka: An Interactive Map of Udupi and Manipal

Suggested Caption field
-----------------------
Created November 7, 2026. An interactive Leaflet map highlighting Manipal,
Udupi Sri Krishna Matha, Malpe Beach and Kapu Lighthouse in coastal Karnataka.

IMPORTANT: The Coursera URL field must contain the PUBLIC URL of the hosted
webpage. Do not put your email address in that field. A local file path or
sandbox download link is not a public webpage URL.

PUBLISH WITH GITHUB PAGES
-------------------------
1. Sign in to GitHub and create a new PUBLIC repository, e.g.
   coastal-karnataka-explorer.
2. Upload index.html to the repository root. You may also upload index.Rmd
   and this README.txt.
3. Open the repository's Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Once GitHub Pages finishes deploying, open the published URL. It will
   normally look like:
   https://YOUR-GITHUB-USERNAME.github.io/coastal-karnataka-explorer/
7. Test the live page and map, then paste the actual published URL into
   Coursera's URL field.

R MARKDOWN SOURCE
-----------------
To render index.Rmd yourself in RStudio:

install.packages(c("rmarkdown", "knitr", "leaflet"))
rmarkdown::render("index.Rmd")

The generated HTML may be placed in a separate output folder. For GitHub
Pages, make sure the final published page is named index.html at the site root.

NOTES
-----
- The interactive map uses Leaflet and online map tiles. Internet access is
  required for the basemap to load.
- The basemap uses the standard OpenStreetMap tile service and credits OpenStreetMap contributors. No Carto API key is required. The map needs an internet connection; do not bulk-download or prefetch tiles for offline use.
- The coordinates are approximate map points for orientation.
- Review and personalize the project before submission. Coursera's Honor
  Code checkbox is an attestation; only agree if your submission complies
  with your course's rules on outside and AI assistance.
