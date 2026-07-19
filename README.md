# Niagara Industrial & Radiological History Map

**Version 0.46 complete master**

This package is ready for deployment with GitHub Pages.

## Files

- `index.html` — the public entry page GitHub Pages opens automatically.
- `Niagara_Interactive_Map_COMPLETE_v0_46.html` — versioned archival copy of the same map.
- `.nojekyll` — tells GitHub Pages to publish the files directly without Jekyll processing.
- `README.md` — package and deployment notes.

## Publish with GitHub Pages

1. Upload all files in this folder to the root of the GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing these files, usually `main`, and choose the `/ (root)` folder.
5. Save. GitHub will provide the public URL after deployment finishes.

The map uses Leaflet and OpenStreetMap resources loaded from the internet. An internet connection is therefore required for the basemap and external library files.


## Interface note
The Leaflet layers control opens and closes by click only; hover expansion is disabled.

- The 2023 aerial-survey outline was redrawn to follow the official October–November 2023 EPA survey-boundary figure supplied by the project.


## Map symbols

Brownfield and redevelopment sites use a magenta diamond. FUSRAP sites use a blue federal-program hexagon with a yellow inset border and white center. FUSRAP means **Formerly Utilized Sites Remedial Action Program**, the federal program for investigating and cleaning up residual radioactive contamination from Manhattan Project and early Atomic Energy Commission activities.
