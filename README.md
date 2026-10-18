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
| `sw.js` | Fait marcher l'app hors connexion et la met à jour toute seule |
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

## Installer sur Android

1. Ouvre l'adresse dans **Chrome**.
2. Touche le menu **⋮** en haut à droite, puis **Installer l'application** (ou **Ajouter à l'écran d'accueil**).
3. Confirme avec **Installer**. Catxpo s'ouvre ensuite en plein écran, comme une app.

## Passer le planning d'un téléphone à l'autre

Dans **Mon planning**, carte **Sauvegarde** :
- **Exporter** crée un fichier de sauvegarde et ouvre le menu de partage (e-mail, WhatsApp, AirDrop…).
  Sur Android, le fichier est envoyé en `.txt` : c'est normal, il s'importe de la même façon.
- Sur l'autre téléphone, enregistre le fichier reçu, puis **Importer** et choisis-le.
  L'import remplace le planning de ce téléphone.

## Bon à savoir

- L'app marche aussi **sans connexion** une fois ouverte une première fois (les liens Google Maps demandent du réseau).
- Après une mise à jour sur GitHub, ferme et rouvre l'app : elle charge la nouvelle version.
- Le planning, le domicile et les notes sont enregistrés **sur chaque appareil** (dans le navigateur). Ils ne sont pas partagés entre deux téléphones.
- La recherche « Chercher partout » (villages, codes postaux), la sauvegarde Google Drive et les notifications de rappel
  fonctionnent uniquement dans la version Catxpo ouverte dans Claude. Ici, les rappels apparaissent sur l'accueil (« À faire : inscriptions »).
- Un dépôt GitHub public est visible par tout le monde : n'y ajoute pas d'informations personnelles.
