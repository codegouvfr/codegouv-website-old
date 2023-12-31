[![Software License](https://img.shields.io/badge/Licence-MIT%2C%20Licence%20Ouverte-orange.svg?style=flat-square)](https://git.sr.ht/~codegouvfr/code.gouv.fr/tree/main/item/LICENSES)

**Attention**: ce dépôt source est l'archive de la version précédente du site [code.gouv.fr](https://code.gouv.fr). Utiliser le nouveau dépôt [github.com/codegouvfr/codegouvfr-website](https://github.com/codegouvfr/codegouvfr-website) (ou son mirroir) pour les développements.

# Site code.gouv.fr

Ce dépôt contient les éléments nécessaires à la publication du site
[code.gouv.fr](https://code.gouv.fr).

Il a été construit à partir de [ce site
modèle](https://github.com/etalab/eleventy-dsfr/).

## Installation et lancement

- Installer les dépendances : `npm install`
- Publier le site : `npx eleventy`
- Publier et rendre le site disponible localement : `npx eleventy --serve`
- Pour que les mises à jour s'affichent automatiquement : `npx eleventy --watch`
- Activer le mode déboguage : `DEBUG=* npx eleventy`

## Déploiement

Le site est déployé en préproduction sur [preprod.codegouv.studio](http://preprod.codegouv.studio) et en production sur [code.gouv.fr](https://code.gouv.fr).

# Contributions

Pour discuter d'évolutions éditoriales ou pour des retours devant
rester confidentiels, écrivez à
[contact@code.gouv.fr](mailto:contact@code.gouv.fr).

Pour des corrections de bug, envoyez vos correctifs (*patches*) à la
liste publique
[~codegouvfr/logiciels-libres@lists.sr.ht](mailto:~codegouvfr/logiciels-libres@lists.sr.ht).

**Attention** à configurer votre copie locale du dépôt de façon à ce
que les correctifs envoyés sur la liste soient bien liés à ce dépôt :

`git config format.subjectPrefix 'PATCH code.gouv.fr'`

## Licences

Le contenu rédactionnel du site est une publication DINUM, 20 avenue de Ségur, 75019, publié sous [licence Ouverte 2.0](LICENSES/LICENSE.Etalab-2.0.md).

Les codes sources de ce dépôt sont publiés sous [licence
MIT](LICENSES/LICENSE.MIT.md).

### Media
- [Blank_man_placeholder.svg](img/bsoc2022/Blank_man_placeholder.svg) par [AntoFran](https://commons.wikimedia.org/wiki/User:AntoFran) sous licence [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0>).
