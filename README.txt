# Aperçu maquette — Valérie Budynek

Ce dossier contient une page `index.html` *noindex* prête à déployer pour montrer la maquette (desktop + mobile).

## Déploiement rapide (au choix)

### A. Sous-domaine sur cre8tive-ai.com (FTP)
1. Créez un sous-domaine, ex. `preview-budynek.cre8tive-ai.com` pointant vers un dossier (ex: `/public_html/preview-budynek`).
2. Uploadez tout le dossier (y compris `/assets`).
3. (Optionnel) Ajoutez une protection par mot de passe avec `.htaccess` (voir `.htaccess.example`).

### B. Netlify (drag & drop)
1. Allez sur app.netlify.com → Sites → **Deploy site** (drag & drop ce dossier).
2. Le site est en ligne avec HTTPS et URL type `*.netlify.app`.
3. Activez la password-protection si besoin.

### C. Vercel (si vous préférez)
1. `vercel deploy` ou import du dossier via l’UI → URL `*.vercel.app`.

## Modifier le contenu
- Ouvrez `index.html` et modifiez les blocs (textes, titres, CTA).
- Remplacez les images dans `/assets/` par vos visuels réels (même noms de fichiers).

## SEO
- La page est livrée avec `<meta name="robots" content="noindex, nofollow">` pour éviter l’indexation.

Bon aperçu !
