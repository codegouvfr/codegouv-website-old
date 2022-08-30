---
title: Les guides
linkTitle: Le pôle logiciels libres vous accompagne dans la mise en oeuvre du plan d'action
layout: page
eleventyNavigation:
  key: Guides
  order: 40
guides:
  - url: https://guides.etalab.gouv.fr/logiciels/
    title: Guide pratique sur l'ouverture des codes sources
    description: |
      Ce guide vous aide à définir vos objectifs en matière d'ouverture des codes sources.
  - url: https://guide-juridique-logiciel-libre.etalab.gouv.fr/
    title: "Guide juridique interactif : quels codes sources ouvrir "
    description: |
      En répondant à quelques questions, faites un point sur vos obligations.
  - url: https://www.data.gouv.fr/fr/pages/legal/licences/
    title: Les licences autorisées pour les codes sources du secteur public
    description: |
      Les codes sources de l'administration peuvent être publiées sous plusieurs licences, parmi lesquelles : Apache, BSD, CeCILL, MPL et les licences du projet GNU.
---

<div class="fr-grid-row fr-grid-row--gutters">

  {% for guide in guides %}
  <div class="fr-col-12 fr-col-md-4">
    <div class="fr-card fr-enlarge-link">
      <div class="fr-card__body">
        <div class="fr-card__content">
          <h2 class="fr-card__title">
            <a href="{{ guide.url }}" class="fr-card__link">{{ guide.title }}</a>
          </h2>
          <p class="fr-card__desc">{{ guide.description }}</p>
        </div>
      </div>
    </div>
  </div>
  {% endfor %}

</div>

<br>

Nous poursuivrons la publication de nouveaux guides tout au long des besoins qui émergeront.

Pour être tenus au courant des nouveaux chantiers, [inscrivez-vous à la gazette BlueHats](https://infolettres.etalab.gouv.fr/subscribe/bluehats@mail.etalab.studio).

Besoin d'aide ou d'accompagnement ?  [Contactez-nous !](mailto:logiciels-libres@data.gouv.fr)
