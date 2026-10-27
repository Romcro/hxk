# Site Haskouil × Krousti

Press kit 2026 du duo, en site statique (HTML, CSS et JS, sans build ni serveur).

- `index.html` : l'accueil, une page de chaîne vidéo. Chaque miniature ouvre une section du press kit.
- `live/` : un faux live, avec chat, alertes et overlays qui déroulent les chiffres.
- `repo/` : le mini-jeu « Mission R.E.P.O », on attrape les semibots pour récupérer les chiffres.
- `kart/` : le bonus kart, un contre-la-montre de 3 tours en clin d'œil à la victoire chez Battle Kart.
- `assets/` : logos, photos, fonds, semibots et la barre de navigation commune (`nav.css`).

## Mettre en ligne

Le site est publié avec **GitHub Pages** depuis la branche `main`, dossier racine (Settings → Pages).
Chaque push sur `main` met le site à jour au bout d'une minute environ.

Autres options : glisser le dossier sur app.netlify.com/drop, ou l'envoyer par FTP dans `www/` chez un hébergeur classique.

## Modifier les chiffres

Les chiffres sont écrits directement dans chaque page (tableau `V` dans `index.html`, `CHAT`, `LOWER` et `ALERTS` dans `live/index.html`, `LOOT` dans `repo/index.html`, `FACTS` dans `kart/index.html`). Garde les mêmes valeurs partout.
