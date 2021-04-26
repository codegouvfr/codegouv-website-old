# Mission interministérielle Green Tech

## Installation

```
npm install
```

## Run

```
npx eleventy
```

Or build and host locally for local development
```
npx eleventy --serve
```

Or build automatically when a template changes:
```
npx eleventy --watch
```

Or in debug mode:
```
DEBUG=* npx eleventy
```

## Déploiement

Déploiement des fichiers statiques de la branche `prod` automatiquement avec les "actions Github" dès commit sur la branche `main`. [Voir le workflow de déploiement](https://github.com/DISIC/greentech/blob/main/.github/workflows/deploy.yml)

## Licence

Ce dépôt est sous [licence Ouverte 2.0](LICENCE.md).
