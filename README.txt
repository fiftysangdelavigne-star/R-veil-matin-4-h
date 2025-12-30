# Réveil Remix — PWA (installable)

## Fichiers
- index.html
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

## Important (PWA)
Pour installer une PWA, il faut **servir** les fichiers via HTTP/HTTPS.
Ça ne marche pas correctement en ouvrant `index.html` en `file://`.

### Option A — Sur ordinateur (facile)
1) Mets tous les fichiers dans un dossier
2) Lance un petit serveur local :
   - Python 3 : `python -m http.server 8080`
3) Ouvre sur ton téléphone la même adresse (même Wi‑Fi) :
   - `http://IP_DE_TON_PC:8080/`

### Option B — Hébergement gratuit
Tu peux mettre le dossier sur GitHub Pages / Netlify / Vercel (site statique).

## Installer sur le téléphone
- Android/Chrome : menu ⋮ → **Installer l'application**
- iPhone/Safari : bouton Partager → **Sur l’écran d’accueil**
