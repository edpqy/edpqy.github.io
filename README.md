# eddypqy.github.io (HugoBlox single-page profile)

This starter pack is set up for:
- HugoBlox theme as a submodule (`themes/hugoblox`)
- A single-page scrolling profile (widgets/blocks)
- 3 highlighted Project cards (GlioPortal, ROS/EZH2, 3D genome/EMT)
- GitHub Actions deployment to GitHub Pages

## Quick start (recommended)

1) Create a repo named: `eddypqy.github.io` (Public)

2) Download this starter pack and copy all files into the repo.

3) Add the HugoBlox submodule:
```bash
git submodule add https://github.com/HugoBlox/hugo-blox-builder themes/hugoblox
git commit -m "Add HugoBlox submodule"
```

(If you already have `.gitmodules`, the above will populate `themes/hugoblox`.)

4) On GitHub: Settings → Pages → Source = **GitHub Actions**

5) Edit your links:
- `content/project/glioportal/index.md` → replace `PUT_YOUR_GLIOPORTAL_URL_HERE`
- `config/_default/params.yaml` → ORCID / socials
- `content/authors/admin/_index.md` → organization, bio

## Local preview
```bash
hugo server -D
```

## Where to edit content
- Homepage sections: `content/_index.md`
- Projects (cards): `content/project/...`
- Selected publications: `content/publication/...`
