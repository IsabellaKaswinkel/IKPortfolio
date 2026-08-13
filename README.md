# Isabella Kaswinkel — Portfolio Site

## What's here
- `index.html` — the full site
- `headshot.jpeg` — your photo, already wired into the hero section
- `Isabella_Kaswinkel_Resume.pdf` — embedded + downloadable
- `assets/Conflict_DeEscalation_Presentation.pdf` — your in-person training deck (compressed from 232MB → 2.3MB, no visible quality loss), embedded in the project modal
- `README.md` — this file

## What's new in this version
- **Clickable projects.** Each project card now opens a full detail view (click anywhere on the card) with more room for context, role, outcome, and embedded materials.
- **Conflict De-Escalation Training project added** — includes your in-person PDF deck embedded and viewable, plus a placeholder slot for the online training video.
- **People Analytics Capstone now includes your full presentation** (compressed from 150MB → ~2MB), embedded and viewable in the modal.
- **Peloton Strategic Analysis project added** — your team's presentation video (45MB, hosted directly, no YouTube needed) plays right in the modal.
- **Work Experience Gallery** (`#gallery` section, between About and Résumé) — a 4-tile click-to-expand gallery for photos/video of your retail and HR work. Currently placeholder tiles; see below to fill them in.

You now have 4 complete projects: People Analytics M&A Capstone, FIFA Player Market Value Analysis, Conflict De-Escalation Training Program, and Peloton Strategic Analysis.

## Still to do

### 1. Add your intro video
Search `REPLACE_WITH_YOUR_VIDEO_ID` in `index.html` (in the top video section) and swap in your YouTube video ID once it's uploaded (Unlisted works fine).

### 2. Add the online training video for the Conflict De-Escalation project
Same idea — search `REPLACE_WITH_TRAINING_VIDEO_ID` in `index.html` and swap in that video's YouTube ID once you've uploaded `Training_DevelopmentProgram.mp4` there (it's 292MB / 12 minutes, too large to host directly in the repo).

### 3. Gallery is complete
`#galleryGrid` in `index.html` now has 7 photos, click-to-expand: 3 from Brandy Melville (team, table display, window display), 3 from your Sheraton Grand internship (Valentine's Day staff gifting, Friday Treat popcorn day, team photo), and 1 from your Carhartt store launch (day-one team photo). Want to swap one out or add more later? Send me the photo and I'll drop it in using this pattern:
   ```html
   <button class="gallery-tile" data-full="assets/gallery/your-photo.jpg" data-type="image">
     <img src="assets/gallery/your-photo.jpg" alt="">
     <span class="cap">Short caption here</span>
   </button>
   ```
   For a video tile, use `data-type="video"` instead.

### 4. Add your intro video and the online training video
These are the last two placeholders left — see items 1 and 2 above.

## Publishing on GitHub Pages
1. Upload every file **and folder** (`index.html`, `headshot.jpeg`, `Isabella_Kaswinkel_Resume.pdf`, and the whole `assets/` folder — which now includes `Capstone_Presentation.pdf`, `Conflict_DeEscalation_Presentation.pdf`, and `Peloton_Strategy_Presentation.mp4`) into your repo, preserving the folder structure — the embedded viewers depend on these exact paths.
2. Go to **Settings → Pages**, set source to `main` branch, `/ (root)` folder, save.
3. Your live URL will be `https://IsabellaKaswinkel.github.io/IKPortfolio/` (based on your repo name) — takes a minute or two to go live.
4. Test on your phone before submitting.

## Canvas submission checklist
- [ ] Comment on submission: "Hybrid Track"
- [ ] Site is public, no login required
- [ ] Tested on phone
