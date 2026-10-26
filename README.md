# Site Haskouil × Krousti : version aléatoire

À chaque visite, `index.html` envoie le visiteur sur une des 4 versions du press kit, tirée au hasard :

- `circuit/` : le circuit automobile
- `combat/` : le jeu de combat
- `live/` : le faux live
- `chaine/` : la chaîne vidéo

Chaque version marche aussi seule avec son adresse directe (ex. `tonsite.fr/live/`).

## Mettre en ligne

Le site est fait de fichiers statiques : aucun serveur particulier, aucune base de données.

- **Netlify (le plus simple, gratuit)** : sur app.netlify.com/drop, glisse le dossier entier. Tu obtiens une adresse en quelques secondes, puis tu peux y brancher ton nom de domaine.
- **Hébergement classique (OVH, o2switch…)** : envoie le contenu du dossier dans `www/` ou `public_html/` par FTP.
- **GitHub Pages** : pousse le dossier dans un dépôt, puis active Pages dans les réglages.

## Retirer ou ajouter une version

Dans `index.html`, modifie la liste `VERSIONS`.
