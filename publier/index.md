---
title: Publier les codes sources du secteur public
linkTitle: Toutes les ressources pour publier vos codes sources
layout: page
eleventyNavigation:
  key: Publier
  order: 20
solutions:
  - url: /public/
    title: code.gouv.fr/public
    description: |
      Les codes sources publiés par les administrations publiques : les dépôts sur GitHub, GitLab ou des instances locales de GitLab.
  - url: /guides/
    title: Les guides
    description: |
      Des ressources pour vous aider à publier vos codes sources sous licence libre : guide pratique, guide juridique et liste des licences autorisées.
  - url: https://www.numerique.gouv.fr/publications/politique-logiciel-libre/
    title: Politique de contribution aux logiciels libres de l’État
    description: |
      Depuis 2018, la politique de contribution aux logiciels libres de l’État guide l'ouverture des codes sources publics et la contribution à des projets tiers.
  - url: https://www.legifrance.gouv.fr/circulaire/id/45162
    title: Circulaire relative à la politique publique de la donnée, des algorithmes et des codes sources
    description: |
      Une nouvelle impulsion pour l'ouverture des codes sources de toutes les administrations.
---

<div class="fr-grid-row fr-grid-row--gutters">

  {% for solution in solutions %}
  <div class="fr-col-12 fr-col-md-6">
    <div class="fr-card fr-enlarge-link">
      <div class="fr-card__body">
        <div class="fr-card__content">
          <h2 class="fr-card__title">
            <a href="{{ solution.url }}" class="fr-card__link">{{ solution.title }}</a>
          </h2>
          <p class="fr-card__desc">{{ solution.description }}</p>
        </div>
      </div>
    </div>
  </div>
  {% endfor %}

</div>

<div class="fr-highlight">
  <p>Besoin d'aide ou d'accompagnement ?  <a href="mailto:contact@code.gouv.fr">Contactez-nous !</a></p>
</div>
