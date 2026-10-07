# Ajaz Ahmad Mir — Academic Website

A GitHub Pages-ready academic research profile inspired by the clean, research-focused layout shown in the reference screenshot.

## Publish on GitHub Pages

1. Create a GitHub repository. For the address `YOURUSERNAME.github.io`, name it `YOURUSERNAME.github.io`.
2. Upload `index.html`, `research.html`, `publications.html`, and the `assets` folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. Your site will be available at `https://YOURUSERNAME.github.io/`.

## Add your photograph

Put your professional photograph at:

`assets/profile.jpg`

Then replace the `.portrait-placeholder` block in `index.html` with:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Ajaz Ahmad Mir">
```

and add:

```css
.profile-photo{width:min(390px,100%);height:395px;object-fit:cover;border-radius:20px}
```

## Personalize

- Replace the Google Scholar `#` link in `index.html` with your profile URL.
- Add ORCID, ResearchGate, LinkedIn, GitHub, etc. if desired.
- The content is based on the supplied CV; verify publication metadata and links before adding DOI links.
