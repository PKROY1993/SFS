# Maine Speed Feedback Message Signs — GitHub Pages Version

This folder contains a simple GitHub Pages-ready project website for the Maine **Speed Feedback Message Signs** project.

## Files
- `index.html` — main project webpage
- `DSFS_SiteVisitMap.kml` — the KML file loaded by the webpage

## What the page does
- Shows the Maine project as a GitHub-ready site
- Keeps the statewide project total visible as **92 locations**
- Loads the uploaded KML dynamically
- Builds a searchable map and site inventory table
- Groups site-visit loops from repeated visit numbering in the KML

## How to publish on GitHub Pages
1. Create a GitHub repository.
2. Upload both `index.html` and `DSFS_SiteVisitMap.kml` to the repository root.
3. Open **Settings → Pages**.
4. Choose the branch and root folder.
5. Save and publish.

## Easy edits
Inside `index.html`, change these values if needed:
- `PROJECT.totalProjectSites` → if your full statewide count changes
- `PROJECT.kmlPath` → if you rename the KML file
- `PROJECT.tripNames` → if you want different trip labels

## Important note
The current KML loads the mapped subset contained in the uploaded file. If you later create a fuller KML with all 92 locations, the page will update automatically after replacing the file.
