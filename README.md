# THE IMAGE THAT REFUSED — complete course project

A complete **single-page HTML artwork** for the assignment *Latent Spaces — AI, Art, and the Archive*.

## Contents

```
the-image-that-refused-final/
├── index.html                  The complete site: layout, styles, interaction, writing
├── assets/
│   ├── family-portrait.jpg     The portrait provided by the student
│   └── salaf-reference.jpg     A documentation image of Salaf (from Somaini's article)
├── .nojekyll                   GitHub Pages compatibility
└── README.md                   This guide
```

## Run locally in VS Code

1. Unzip the project and open the **folder** in VS Code (File → Open Folder).
2. Double-click `index.html` in the file explorer, or right-click it and choose to open it in your browser.
3. Click the large button through four states: DETECT → CLASSIFY → REDUCE → REFUSE.
4. Scroll down to see the alternative taxonomy, source artwork, Part A, and Part B.

No installation, build command, framework, live AI API, or database is required.

## Publish on GitHub Pages

1. In VS Code Source Control, initialize a Git repository if one is not yet initialized.
2. Stage all the files, Commit, and select **Publish to GitHub** to create a GitHub repository.
3. In the repository on github.com: **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then Save.
5. Use GitHub's **Visit site** link once deployment finishes.

The published URL typically looks like `https://YOUR-USERNAME.github.io/the-image-that-refused/`.

## Sources and editorial decisions

- Source artwork: Nouf Aljowaysir, [*Salaf (Ancestors)*](https://www.noufaljowaysir.com/work/salaf). The site attempts to display the specifically selected **Salaf #2102 — Woman with jewelry** from the artist’s website. If that remote image is unavailable, it falls back to an academic-documentation montage drawn from the scholarly article cited below. The artwork remains © Nouf Aljowaysir; permission to reproduce should be confirmed for a public site.
- Scholarly article: Antonio Somaini (2026), [“Latent Spaces: AI, Art, and the Archive,”](https://doi.org/10.1162/OCTO.a.545) *October* 196, 18–60, especially p. 46.
- The portrait comes from the student's personal image supplied for this project. Confirm that public posting is intended before enabling GitHub Pages.
- The **classifier is a staged fictional interface**, not the result of running a machine learning model. The labels are part of the artwork. The website does not upload images or record user behavior.
- All content on the site is in English; Part A contains the required three responses and quotation, Part B describes method/tools, and a separate three-sentence explanation addresses how the new work responds to the original.

## Editing the project

- Edit English text directly in `index.html` using VS Code.
- Adjust stage labels and descriptions in the `scenes` array near the end of `index.html`.
- Replace `assets/family-portrait.jpg` with a different portrait using exactly that filename.
- The original artwork area uses the remote image **Salaf #2102** and falls back to `assets/salaf-reference.jpg` if unavailable. If you obtain a licensed local copy of #2102, save it in `assets` and change the `src` of the image in the Salaf section of `index.html` to the relative file path.

## Checklist before submission

- [ ] Confirm the portrait can appear on a public website.
- [ ] Confirm whether the *Salaf* documentation image may be reproduced online, or replace it with an authorized image.
- [ ] Read through Part A and verify it reflects your interpretation.
- [ ] Change the author credit if your instructor requires your name; do not publish private details unnecessarily.
- [ ] Test the interaction, mobile layout, GitHub Pages links, and image loading after deployment.
