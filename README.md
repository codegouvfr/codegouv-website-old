# Site communs.numerique.gouv.fr

Ce dépôt contient les éléments nécessaires à la publication du site
[communs.numerique.gouv.fr](https://communs.numerique.gouv.fr).

Il a été construit à partir de [ce site
modèle](https://github.com/etalab/eleventy-dsfr/).

## Installation et lancement

- Installer les dépendances : `npm install`
- Publier le site : `npx eleventy`
- Publier et rendre le site disponible localement : `npx eleventy --serve`
- Pour que les mises à jour s'affichent automatiquement : `npx eleventy --watch`
- Activer le mode déboguage : `DEBUG=* npx eleventy`

## Déploiement

Le site est déployé en préproduction sur [communs.etalab.studio](https://communs.etalab.studio) à partir du répertoire `_site` de la branche `master` et en production sur [communs.numerique.gouv.fr](https://communs.numerique.gouv.fr) à partir du répertoire `_site` de la branche `production`.

# Contributions

Vos contributions sont les bienvenues !

Pour des retours d'anomalie ou des propositions de contributions sur
l'un de ces dépôts, merci d'écrire à la liste de discussion *publique*
[~etalab/logiciels-libres@lists.sr.ht](mailto:~etalab/logiciels-libres@lists.sr.ht).

Pour les retours devant rester confidentiels (failles de sécurité,
demandes personnelles, etc.), écrivez à [logiciels-libres@data.gouv.fr](mailto:logiciels-libres@data.gouv.fr).

## Licences

[![Software License](https://img.shields.io/badge/Licence-MIT%2C%20Licence%20Ouverte-orange.svg?style=flat-square)](https://git.sr.ht/~etalab/communs.numerique.gouv.fr/tree/main/item/LICENSES)

Le contenu rédactionnel du site est une publication DINUM, 20 avenue de Ségur, 75019, publié sous [licence Ouverte 2.0](LICENSES/LICENSE-etalab-2.0.txt).

Les codes sources de ce dépôt sont publiés sous [licence
MIT](LICENSES/LICENSE-MIT.md).
