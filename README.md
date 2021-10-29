# Plan d'action logiciels libres et communs numériques

Ce dépôt contient les éléments nécessaires à la publication du site
[communs.numerique.gouv.fr](https://communs.numerique.gouv.fr).

Il a été construit à partir de [ce site
modèle](https://github.com/etalab/eleventy-dsfr/).

## Installation et lancement

Pour installer les dépendances:

```
npm install
```

Pour publier le site:

```
npx eleventy
```

Pour le publier et rendre le site disponible localement:

```
npx eleventy --serve
```

Pour le publier et que les mises à jour s'affichent automatiquement:

```
npx eleventy --watch
```

Activer le mode déboguage:

```
DEBUG=* npx eleventy
```

## Déploiement

Le site est déployé à partir du répertoire `_site` de la branche `master`.

## Licence

Le contenu rédactionnel du site est une publication DINUM, 20 avenue de Ségur, 75019, publié sous [licence Ouverte 2.0](LICENSES/LICENSE-etalab-2.0.txt).

Les codes sources de ce dépôt sont publiés sous [licence MIT](LICENSES/LICENSE-MIT.md).

