# sridevi-tandley.github.io

Personal academic website of Dr. Sridevi Tandley — plain HTML and CSS, no build step, hosted on GitHub Pages.

Live address once published: **https://sridevi-tandley.github.io/**

## Publish it (one-time, about ten minutes, no software needed)

1. **Sign in** at https://github.com as **sridevi-tandley** (create the account with that exact username if it does not exist yet — the site address comes from the username).
2. **Create the repository**: click the **+** at the top right → **New repository**. Name it exactly `sridevi-tandley.github.io`, set it to **Public**, leave "Add a README" unticked, click **Create repository**.
3. **Upload the files**: on the empty-repository page click **uploading an existing file**. Open the `sridevi-tandley.github.io` folder on your computer, select *everything inside it* (the `.html` files, `README.md`, `.nojekyll`, `robots.txt`, `sitemap.xml`, and the `assets` and `cv` folders) and drag them onto the upload area — dragging the folders keeps their structure. Wait for all uploads to finish (the film in `assets/video` is about 7 MB and takes the longest), type a message such as "First upload", and click **Commit changes**.
4. **Check the structure**: the repository home should now list `index.html` at the top level and the `assets` and `cv` folders. If you see a single `sridevi-tandley.github.io` folder inside the repository instead, you dragged the parent folder — delete it and upload the contents again.
5. **Turn on Pages**: **Settings** (repository tab) → **Pages** (left menu) → under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)** → **Save**.
6. **Wait one or two minutes**, then open https://sridevi-tandley.github.io/ . Check that the photo, the CV PDF and the film on the *AI Agents at Work* page all load. Pages sometimes needs one refresh after the first deploy.

The BIM faculty page links to this address as **Website**, to `cv/Sridevi_Tandley_CV.pdf` as **CV**, and to `ai-agents-at-work.html` from the *AI Agents at Work* corner card — so those links go live at the same moment.

If you prefer a desktop tool: install **GitHub Desktop**, *File → Clone repository* → pick `sridevi-tandley.github.io`, copy the folder contents into the cloned folder, then *Commit to main* and *Push origin*. Step 5 is still needed once.

## Update it later

* Edit any `.html` file in a text editor and re-upload it (or commit) — the site updates within a minute.
* Replace `cv/Sridevi_Tandley_CV.pdf` (and the `.docx`) to publish a new CV; the CV page and the Home page link to that fixed filename.
* Replace `assets/photo.jpg` (portrait, 3:4) to change the photograph.
* Replace `assets/video/AgenticAI_Build_Process.mp4` (and the `_poster.jpg`) to change the companion film on the *AI Agents at Work* page.
* New paper: add an entry in `research.html` under the right heading, and — if it is recent — in the *Recent work* list on `index.html`.
* New workshop or talk: see *Adding a new entry* below.

## Adding a new entry (for example a corporate workshop) — about five minutes

**Route A — replace the whole file (simplest).** Edit the page on your computer (or use the updated copy provided), then in the repository click **Add file → Upload files**, drag the changed file(s) — for example `teaching.html`, `index.html` and `sitemap.xml` — onto the upload area, type a message such as "Add Forbes Advisor workshop", and click **Commit changes**. The upload replaces the old file with the same name. The site refreshes within a minute or two; press Ctrl+F5 on the page if you still see the old text.

**Route B — edit in the browser.** Open the repository, click `teaching.html`, then the **pencil icon** (Edit this file) at the top right of the file view. Find the line `<h2 id="training">Corporate &amp; Professional Training</h2>` (Ctrl+F). Directly after the `<ul class="clean">` line that follows it, paste a new entry in this shape:

```html
<li><b>Workshop title</b> — Organisation, City, Month Year: one or two sentences on who attended and what they did. </li>
```

Click **Commit changes…**, keep "Commit directly to the main branch", and commit. Entries are listed most recent first, so a new one always goes at the top of the list.

**After either route**, update the `<lastmod>` date for the pages you changed in `sitemap.xml` (same pencil-icon method), and check the live page at https://sridevi-tandley.github.io/teaching.html#training.

Writing style for entries: title in bold, then organisation, place and month; one sentence on the audience and what they did; one sentence of outcome or feedback if you have it. Keep to the facts of the session — the site does not name client-side individuals.

## Files

```
index.html       Home — photo, bio, contact links, recent work
research.html    Working papers, presentations, articles and chapters, reports, work in progress
teaching.html    Courses designed, corporate learning, conferences & lectures, teaching interests, academic roles
industry.html    Applied projects led from BIM, career, client exposure, specialisations
ai-agents-at-work.html  Masterclass companion — build-process film, six steps, four blocks, key insights
cv.html          CV page with embedded PDF and download
404.html         Not-found page served by GitHub Pages
robots.txt, sitemap.xml   Search-engine hints (update lastmod dates when you change pages)
assets/          style.css, photo.jpg, photo-square.jpg, video/AgenticAI_Build_Process.mp4 (+ poster)
cv/              Sridevi_Tandley_CV.pdf, Sridevi_Tandley_CV.docx
.nojekyll        tells GitHub Pages to serve the files as they are
```
