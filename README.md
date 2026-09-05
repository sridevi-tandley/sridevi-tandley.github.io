# sridevi-tandley.github.io

Personal academic website of Dr. Sridevi Tandley 

Live address once published: **https://sridevi-tandley.github.io/**

## Publish it 

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
