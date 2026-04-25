# Week 2 Portfolio — Alex Mwangi

A 4-page personal portfolio website built with plain HTML5 and CSS3
as part of a web development bootcamp Week 2 challenge.

---

## Folder Structure

```
week2-portfolio/
├── index.html           ← Homepage (welcome, intro, quick-facts table)
├── about.html           ← Background, skills list, goals, resources
├── projects.html        ← 3 projects with images and summary table
├── contact.html         ← Email, social links, response-times table
└── images/
    ├── workspace.jpg         (index.html — your desk photo)
    ├── profile.jpg           (about.html — your headshot)
    ├── nairobi.jpg           (contact.html — city/location photo)
    ├── project-recipe.jpg    (projects.html — Recipe Finder screenshot)
    ├── project-portfolio.jpg (projects.html — this site screenshot)
    └── project-dashboard.jpg (projects.html — dashboard wireframe)
```

---

## Adding Your Images

Place your own photos inside the `/images` folder using the filenames above.
Free images can be downloaded from https://unsplash.com or https://picsum.photos.

---

## Deploying to GitHub Pages

```bash
cd ~/projects/week2-portfolio
git init
git add .
git commit -m "Complete Week 2 Portfolio Challenge"
git branch -M main
git remote add origin https://github.com/yourusername/week2-portfolio.git
git push -u origin main
```

Then: Repo → Settings → Pages → Deploy from **main** branch / root folder.
Live URL: `https://yourusername.github.io/week2-portfolio/`

---

## Requirements Checklist

| Requirement                                    | Covered In                          |
|------------------------------------------------|-------------------------------------|
| Proper HTML structure on every page            | All 4 pages                         |
| Unique `<title>` per page                      | All 4 pages                         |
| Working navigation (links to all pages)        | All 4 pages                         |
| At least one heading and paragraph per page    | All 4 pages                         |
| All heading levels h1–h6 used                  | Spread across all pages             |
| 2+ lists (ordered and unordered)               | about.html, contact.html, projects  |
| 5+ images with alt text                        | index, about, projects ×3, contact  |
| `<figure>` with `<figcaption>`                 | index.html                          |
| Table with `<thead>`, `<tbody>`, `<caption>`   | index, projects, contact            |
| `mailto:` link                                 | contact.html + every footer         |
| 3+ external links                              | about.html resources + socials      |
| `<strong>` used at least once                  | index, about, projects, contact     |
| `<em>` used at least once                      | index, about, projects, contact     |
