# Dr Sathish Kumar Marimuthu — Academic website

A responsive, dependency-free static academic website. No installation or build step is needed. Open `index.html` for a local preview.

## Publish on GitHub Pages

1. Sign in to GitHub and create a **public** repository named `YOUR-USERNAME.github.io`, replacing YOUR-USERNAME with your actual GitHub username. This publishes at `https://YOUR-USERNAME.github.io/`. If that repository already exists, use it and preserve any files you need.
2. Unzip the download on your computer. Upload the **contents** of the `sathish-academic-website` folder to the repository root: `index.html`, `styles.css`, `assets/`, `.nojekyll`, and `README.md`. Do not upload the ZIP or a wrapping folder. Use **Add file → Upload files**, then commit to `main`. Hidden files may need to be enabled to see `.nojekyll`; if missing, use **Add file → Create new file** to create `.nojekyll` with a blank line.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Choose branch **main**, folder **/(root)**, then **Save**.
6. Wait for the Pages deployment to finish (check the repository's **Actions** tab). Open the site URL shown in **Settings → Pages**. Publishing can take up to ten minutes.
7. Check the site on a phone and confirm the **Download CV** and DOI links work.

Alternatively, use a public repository named `academic-website`. The same root-folder setup publishes at `https://YOUR-USERNAME.github.io/academic-website/`. All local links are relative and work for either arrangement. No custom domain or account username is hard-coded.

Official guidance: [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart) and [publishing source configuration](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Edit later

- **Content:** edit the clearly identified `<section id="…">` blocks in `index.html`. Each publication is an `<article class="publication">`; copy an existing article to add a paper and replace its citation and DOI.
- **Design:** edit the colours and layout rules in `styles.css`. Mobile layouts are defined at the bottom of that file.
- **CV:** the public download is `assets/sathish-kumar-marimuthu-cv.pdf`. An editable printable HTML version sits beside it. Edit that HTML, open it in a browser, and use Print → Save as PDF (A4, headers/footers off) to replace the PDF under the same filename.
- **Contact:** update the email in `index.html` and the public CV together.
- Commit changes to `main` to republish automatically. Keep local asset paths relative, without an initial `/`.

## Content and privacy notes

Content was organised from the uploaded CV. Appointment dates and funding roles are preserved as supplied. The 2026 emulator DOI, absent from the CV, was verified against the University of Glasgow publication record: https://eprints.gla.ac.uk/392904/ . The other two DOIs were supplied in the CV.

The phone number and complete referee section are excluded from both the site and the downloadable public CV. The original private DOCX is deliberately not included in this repository. The public CV is an organised edition, not a facsimile of the uploaded document.

The CV supports aortic stent-graft mechanics, growth/remodelling, patient-specific modelling, cardiovascular emulation and a position in Future PCI Planning. It does not specify distinct EVAR/FEVAR projects or an independent PCI-planning project, so those achievements have not been invented. No planned fellowship, unpublished manuscript or unconfirmed collaboration from the earlier conversation is presented as an achievement.

The site uses system fonts, local assets, semantic HTML, keyboard focus styles, a skip link, reduced-motion support and responsive layouts. It has no analytics, tracking, external fonts, framework, or package dependencies.
