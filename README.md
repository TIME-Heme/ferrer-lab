# Ferrer Lab website

A single-page static site for the Translational Immunology and Epigenetics Laboratory in Hematological Neoplasms. Open `index.html` in a browser to preview. The site uses HTML and CSS with local assets.

```text
.
├── .nojekyll          # Serve files directly on GitHub Pages
├── index.html        # Lab content and page structure
├── styles.css        # Design tokens and responsive layouts
├── assets/
│   ├── ijc.svg       # Official IJC English logo
│   ├── sjd.svg       # Official SJD header logo
│   ├── google.png    # Google wordmark
│   └── ub.png        # Universitat de Barcelona logo
└── README.md
```

## Editing the page

- Change colors, typography, spacing, or logo sizes in the commented `:root` block of `styles.css`.
- Edit names, roles, research descriptions and email links in `index.html`. Duplicate a team article or publication list item to add an entry. The PI has a dedicated featured biography.
- To add a LinkedIn snapshot, save the image in `assets/` and replace the initials in the corresponding portrait element in `index.html` with an image. Remove `aria-hidden="true"` from that portrait element and add the member’s name as the image’s alternative text.
- To change the location, update the printed address, Google Maps link and iframe query in the contact section.
- Replace the local SVGs with updated institutional artwork as needed. The originals are from the [IJC English homepage](https://www.carrerasresearch.org/en/) the [SJD English homepage](https://www.sjdhospitalbarcelona.org/en), [Google](https://www.google.com/), and [Universitat de Barcelona](https://web.ub.edu/en/).
- Publication titles link to primary records. The selection balances relevant topics, dates, and contributions from the PI and team.

## Publishing on GitHub Pages

1. Put these files at the root of a public GitHub repository and push the publishing branch, typically `main`.
2. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the publishing branch and **/(root)**, then save. GitHub shows the live URL on the same settings page when deployment succeeds.

[GitHub Pages publishing documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
