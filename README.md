# Catxpo

Application web pour planifier les expositions félines avec un **Maine Coon polydactyle** :
calendrier mondial des expositions TICA (seule fédération qui accepte les polydactyles en championnat),
expos des autres fédérations en Belgique, France, Pays-Bas, Allemagne et Angleterre,
adresses des salles, distances, itinéraires Google Maps et planning personnel avec checklist.

Données : calendrier officiel TICA et sites des clubs, consultés en octobre 2026 (saison 2026–2027).

## Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | L'application complète |
| `cities.txt` | 135 233 villes du monde (recherche du lieu de départ) |
| `manifest.webmanifest`, `icon-*.png` | Installation sur l'écran d'accueil (iPhone, Android) |
| `.nojekyll` | Indique à GitHub Pages de publier les fichiers tels quels |

## Mettre en ligne avec GitHub Pages

1. Sur github.com, clique sur **New repository**, nomme-le par exemple `catxpo`, laisse-le **Public**, puis **Create repository**.
2. Clique sur **uploading an existing file**, glisse **tous les fichiers de ce dossier** (pas le dossier lui-même), puis **Commit changes**.
   Le fichier `.nojekyll` est caché sur certains ordinateurs : il n'est pas indispensable.
3. Va dans **Settings → Pages**. Sous **Branch**, choisis `main` et `/ (root)`, puis **Save**.
4. Après une ou deux minutes, l'adresse s'affiche : `https://<ton-nom>.github.io/catxpo/`.

## Installer sur un iPhone

1. Ouvre l'adresse dans **Safari**.
2. Touche le bouton **Partager** (carré avec une flèche vers le haut).
3. Choisis **Sur l'écran d'accueil**, puis **Ajouter**. L'icône Catxpo apparaît comme une app.

## Bon à savoir

- Le planning, le domicile et les notes sont enregistrés **sur chaque appareil** (dans le navigateur). Ils ne sont pas partagés entre deux téléphones.
- La recherche « Chercher partout » (villages, codes postaux), la sauvegarde Google Drive et les notifications de rappel
  fonctionnent uniquement dans la version Catxpo ouverte dans Claude. Ici, les rappels apparaissent sur l'accueil (« À faire : inscriptions »).
- Un dépôt GitHub public est visible par tout le monde : n'y ajoute pas d'informations personnelles.
