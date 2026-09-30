# Murilo Góes de Almeida — Personal site

Static bilingual portfolio prepared for GitHub Pages.

The site is organized as a concise professional profile with two supporting pages:

- `index.html` — profile, experience, expertise and contact;
- `research.html` — publications and academic profiles;
- `resources.html` — classes, repositories and open materials.

## Local preview

Open a terminal in this folder and run:

```powershell
python -m http.server 4173
```

Then open `http://localhost:4173`.

## Publish at `murilogoes.github.io`

1. Create a public GitHub repository named exactly `murilogoes.github.io`.
2. Open a terminal in this folder.
3. Run:

```powershell
git init
git add .
git commit -m "Create personal portfolio"
git branch -M main
git remote add origin https://github.com/murilogoes/murilogoes.github.io.git
git push -u origin main
```

The page should become available at `https://murilogoes.github.io` after GitHub Pages finishes the first deployment.

Future updates only require:

```powershell
git add .
git commit -m "Update portfolio"
git push
```
