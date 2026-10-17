# Guide Monstera

Application web installable (PWA) pour suivre vos monstera : variétés, soins, bouturage, parasites, météo et analyse de photo.

## Installer depuis GitHub (sans ligne de commande)

1. Créez un compte sur github.com, puis un nouveau dépôt **public** nommé `monstera` (Pages est gratuit pour les dépôts publics).
2. Dans le dépôt : Add file, Upload files. Glissez tous les fichiers de ce dossier (index.html, manifest.webmanifest, sw.js, les deux icônes, README.md), puis Commit changes.
3. Settings, Pages. Source : Deploy from a branch. Branche : main, dossier : / (root). Enregistrez.
4. Après une à deux minutes, l'application est en ligne à l'adresse `https://VOTRE-PSEUDO.github.io/monstera/`.
5. Ouvrez cette adresse dans Chrome sur Android, puis menu ⋮, Installer l'application.

Pour mettre à jour : remplacez index.html dans le dépôt (Add file, Upload files). Les téléphones récupèrent la nouvelle version à la prochaine ouverture avec connexion.

## Obtenir un fichier APK

Une fois l'adresse GitHub Pages en ligne, collez-la sur pwabuilder.com, choisissez Android et téléchargez le paquet.

## À savoir

- Vos plantes et photos restent sur le téléphone. Rien n'est envoyé dans le dépôt.
- Analyse de photo : enregistrez votre clé API Anthropic dans l'application (onglet Mes monstera). La clé reste sur le téléphone, jamais dans le dépôt, et chaque analyse est facturée à votre compte API. Utilisez une clé dédiée avec une limite de dépense.
- « Utiliser ma position » récupère la météo extérieure via Open-Meteo. Seule la position arrondie à environ 10 km est conservée.
