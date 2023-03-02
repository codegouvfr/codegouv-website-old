---
title: Développements
linkTitle: Nous développons des logiciels libres pour les administrations
layout: page
eleventyNavigation:
  key: Dev
  order: 40
repos:
  - url: https://github.com/codegouvfr/react-dsfr
    title: react-dsfr
    description: |
      Une bibliothèque de composants React au DSFR
  - url: https://www.onyxia.sh
    title: Onyxia
    description: |
      La stack data science moderne rendue accessible
---

<div class="fr-grid-row fr-grid-row--gutters">

  {% for repo in repos %}
  <div class="fr-col-12 fr-col-md-4">
    <div class="fr-card fr-enlarge-link">
      <div class="fr-card__body">
        <div class="fr-card__content">
          <h2 class="fr-card__title">
            <a href="{{ repo.url }}" class="fr-card__link">{{ repo.title }}</a>
          </h2>
          <p class="fr-card__desc">{{ repo.description }}</p>
        </div>
      </div>
    </div>
  </div>
  {% endfor %}

</div>
