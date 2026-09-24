# Enxhi Leka’s website

A plain HTML and CSS academic website for GitHub Pages. No build step, package installation, or JavaScript is required.

## Preview locally

1. Open this repository folder in Visual Studio Code (File → Open Folder).
2. Install the **Live Server** extension by Ritwick Dey if needed.
3. Right-click **index.html** and select **Open with Live Server**.
4. Use the Home, Research, Teaching, and CV links. Saved edits refresh automatically.

You can also double-click index.html to open it directly in your browser; a local server gives a more consistent PDF preview.

## Edit content

- index.html: biography, research interests, and education.
- research.html: papers, conferences, seminars, and talks.
- teaching.html: courses and institutions.
- cv.html: CV viewer and download links.
- assets/cv.pdf: replace this file to update the CV (keep the filename).
- assets/style.css: shared colors, typography, spacing, and mobile layout.

The header and footer are intentionally plain HTML. To change navigation or contact details, update all four HTML files.

## Publish with GitHub Pages

1. In GitHub Desktop, review the changes, write a commit summary, click **Commit to main**, then **Push origin** (or **Publish repository** if needed). Keep the repository public for GitHub Free.
2. On GitHub, open the repository → **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you pushed (normally **main**) and **/(root)**, then **Save**.
5. When deployment finishes, visit https://enxhileka.github.io/.

The .nojekyll file tells GitHub Pages to serve the static files directly. All internal links are relative, so local previews and GitHub Pages both work.

## Content source

Migrated from https://sites.google.com/view/enxhi-leka/ on 24 September 2026. Original sections and factual content are retained; spacing, capitalization, and date presentation are normalized. The CV is the original public PDF from the existing site. No analytics, external fonts, or third-party scripts are loaded.

Original page banner photographs and the IMT Business School logo are stored locally in assets/images/. Each page uses its corresponding original banner.

## Add a news update

Open index.html and search for the NEWS comment. Inside the News box, remove the “Updates coming soon.” paragraph and copy the article example from the comment into the visible HTML (outside the comment). Set the date and update text; place newer articles first. You may include links to papers, events, or other pages. Save to refresh the preview, then commit and push to publish.
