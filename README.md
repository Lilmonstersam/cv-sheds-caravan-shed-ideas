# CV Sheds Caravan Shed Ideas Mockup

Static HTML mockup for the long-form "15 Caravan Shed Ideas" article.

## What is included

- `index.html`: self-contained page mockup with CSS and lightweight JavaScript.
- Sticky desktop table of contents, mobile jump menu and reading progress bar.
- Real CV Sheds gallery images embedded from the existing garages and carports galleries.
- GitHub Pages friendly Vite config using `base: "/cv-sheds-caravan-shed-ideas/"`.
- GitHub Actions workflow for Pages deployment.

## Local preview

```bash
npm install
npm run dev
```

Open the local Vite URL shown in the terminal.

## Build

```bash
npm run build
```

## Push to GitHub

```bash
git init
git remote add origin https://github.com/Lilmonstersam/cv-sheds-caravan-shed-ideas.git
git add .
git commit -m "Add CV Sheds caravan shed ideas mockup"
git branch -M main
git push -u origin main
```

After pushing, enable GitHub Pages from GitHub Actions if it is not already enabled for the repository.
