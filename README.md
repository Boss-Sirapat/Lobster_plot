# LOBSTER plot viewer

A standalone browser viewer for standard COHPCAR.lobster, COOPCAR.lobster, and pairwise COBICAR.lobster files.

## Use

Open `index.html` in a browser, select your files, and click **Load selected files**. Files are parsed locally in the browser.

- Choose an interaction and spin display.
- Adjust energy and X ranges or use automatic X scaling.
- Set automatic or manual tick intervals for both axes.
- Save plots as PNG (2280 × 3060) or SVG, or export curve data as CSV.
- COHP curves are green, COOP orange, and COBI purple.

The default COHP representation is −pCOHP. The energy column is plotted as supplied; the EF marker is at zero, so use energy data referenced to the Fermi level.

Arial Rounded MT Bold is used when installed, with Arial as a fallback.

## GitHub Pages

Place `index.html` and `.nojekyll` at the root of the publishing branch. In repository Settings → Pages, select **Deploy from a branch**, choose that branch and **/ (root)**, then Save.

Expected address after deployment: LOBSTER-COHP-COOP-COBI-plot.html

## Supported input

Standard pairwise CAR tables with one or two spin channels, including orbital-resolved columns. Integrated ICOXXLIST files and multi-center COBI layouts are not supported. Check the file status for truncation warnings.
