[![Software License](https://img.shields.io/badge/Licence-MIT%2C%20Licence%20Ouverte-orange.svg?style=flat-square)](https://git.sr.ht/~etalab/communs.numerique.gouv.fr/tree/main/item/LICENSES)

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

Le site est déployé en préproduction sur [communs.etalab.studio](https://communs.etalab.studio) et en production sur [communs.numerique.gouv.fr](https://communs.numerique.gouv.fr).

# Contributions

Pour discuter d'évolutions éditoriales ou pour des retours devant
rester confidentiels, écrivez à
[logiciels-libres@data.gouv.fr](mailto:logiciels-libres@data.gouv.fr).

Pour des corrections de bug, envoyez vos correctifs (*patches*) à la
liste publique
[~etalab/logiciels-libres@lists.sr.ht](mailto:~etalab/logiciels-libres@lists.sr.ht).

**Attention** à configurer votre copie locale du dépôt de façon à ce
que les correctifs envoyés sur la liste soient bien liés à ce dépôt :

`git config format.subjectPrefix 'PATCH communs.numerique.gouv.fr'`

## Licences

Le contenu rédactionnel du site est une publication DINUM, 20 avenue de Ségur, 75019, publié sous [licence Ouverte 2.0](LICENSES/LICENSE.Etalab-2.0.md).

Les codes sources de ce dépôt sont publiés sous [licence
MIT](LICENSES/LICENSE.MIT.md).
