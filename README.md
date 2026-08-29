# MRXtra GitHub Pages Website

This folder contains a complete static website for the MRXtra research project.

## Files

- `index.html` — page content
- `styles.css` — styling and responsive layout
- `script.js` — mobile navigation
- `assets/mrxtra-mark.svg` — simple temporary project mark
- `publications/` — place public abstracts/publications here

## 1. Upload to your GitHub repository

Upload the contents of this folder to the ROOT of your `MRXtra` repository.

Your repository should look like:

```text
MRXtra/
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── mrxtra-mark.svg
└── publications/
    └── README.md
```

Do not upload the outer `MRXtra_GitHub_Pages` folder itself unless you intend to serve the site from a subdirectory.

## 2. Edit these placeholders before launch

Search `index.html` for:

- `YOUR_EMAIL@example.com`
- `YOUR_USERNAME`

Replace them with your public email address and GitHub username.

Also review the Funding & Collaboration section and add the exact institutional acknowledgements required by the MICCAI award and your collaborators.

## 3. Enable GitHub Pages

In your GitHub repository:

1. Go to **Settings**
2. Choose **Pages**
3. Under **Build and deployment**, select **Deploy from a branch**
4. Select the `main` branch
5. Select `/(root)`
6. Save

Your public URL will normally be:

`https://YOUR_USERNAME.github.io/MRXtra/`

## 4. Add the accepted AMAI-MICCAI 2026 abstract

When you are ready to make the accepted abstract public:

1. Upload the PDF to:
   `publications/AMAI-MICCAI-2026-Abstract.pdf`
2. Open `index.html`
3. Find:
   `Abstract PDF coming soon`
4. Replace the disabled link with:

```html
<a class="button secondary"
   href="publications/AMAI-MICCAI-2026-Abstract.pdf"
   target="_blank"
   rel="noopener">
  View accepted abstract
</a>
```

5. Commit the change.

Later, when the official proceedings/DOI becomes public, point this button to the official publication page. Your poster QR code can remain unchanged because it points to the MRXtra homepage.

## 5. Clinical study data used on this page

The clinical evidence section is based on the uploaded manuscript:

**Clinical Feasibility of an Upstream AI-Assisted Decision Support System for MRI Safety Screening and Protocol Optimization in a Nigerian Tertiary Center**

Key values reproduced in the site:

- 160 consecutive patients: 80 baseline and 80 MRXtra
- Screening completeness: 53.8% → 96.3%, p < 0.001
- Contraindications detected: 2 → 15, p = 0.001
- Median total workflow time: 105 → 78 minutes, p < 0.001
- SUS: 79.0 ± 4.6, n = 5 radiographers
- 80 protocol suggestions
- 70% accepted without modification
- 20% modified
- 10% overridden
- Estimated SAR 0.46–1.92 W/kg
- Seven logged technical/workflow adverse events; all resolved without patient harm

The page deliberately describes the work as a **completed single-centre clinical feasibility evaluation**, not as a preliminary study.

## 6. Before public launch

Check:

- [ ] Contact email
- [ ] GitHub repository link
- [ ] Team/institution names
- [ ] Exact grant acknowledgement
- [ ] Collaborator acknowledgements
- [ ] Accepted abstract PDF, if permitted
- [ ] Any logo/image permissions
- [ ] No patient-identifiable information
- [ ] No passwords, API keys, IP addresses, internal server details or source-code secrets

## 7. Recommended next upgrade

Once the basic site is live, add:

- an MRXtra workflow/architecture figure
- a project team section
- institutional logos if permission allows
- a publications list with DOI links
- a permanent contact email
- optional custom domain such as `mrxtra.org` if the project matures
