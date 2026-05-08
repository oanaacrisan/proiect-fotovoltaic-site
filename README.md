# Proiect Fotovoltaic - site static

Site de prezentare pentru un proiect cu fonduri europene privind instalarea de panouri fotovoltaice.

## Tehnologie

- HTML, CSS si JavaScript simplu
- Site static, fara baza de date
- Structura pregatita pentru publicare pe Vercel
- Comutator RO/EN in header, fara API extern

## Structura

```text
.
├── index.html
├── despre-proiect.html
├── obiective.html
├── finantare.html
├── anunt-demarare.html
├── contact.html
├── robots.txt
├── sitemap.xml
└── assets
    ├── css/styles.css
    ├── js/main.js
    └── images
        ├── hero-panouri-fotovoltaice.png
        └── logos/
```

## Rulare locala

Varianta simpla:

1. Deschide folderul in Visual Studio Code.
2. Deschide `index.html` in browser.

Varianta recomandata in VS Code:

1. Instaleaza extensia `Live Server`.
2. Click dreapta pe `index.html`.
3. Alege `Open with Live Server`.

## Ce trebuie completat inainte de publicare

- Domeniul actual folosit in `robots.txt` si `sitemap.xml`: `https://oct-sunenergy.vercel.app`
- Confirmarea finala ca logo-urile UE si Guvernul Romaniei sunt acceptate de ghidul programului exact

## Publicare pe GitHub

Dupa ce continutul este verificat:

```bash
git init
git add .
git commit -m "Initial static project website"
git branch -M main
git remote add origin https://github.com/oanaacrisan/proiect-fotovoltaic-site.git
git push -u origin main
```

## Publicare pe Vercel

1. Intra in contul Vercel.
2. Alege `Add New Project`.
3. Importa repository-ul GitHub.
4. La framework selecteaza `Other` sau lasa detectarea implicita.
5. Nu este nevoie de build command.
6. Seteaza output directory la radacina proiectului daca Vercel cere acest lucru.
7. Apasa `Deploy`.

Nu introduce chei API in frontend.
