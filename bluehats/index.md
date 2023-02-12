---
title: Mobiliser via les initiatives BlueHats 🧢
layout: page
eleventyNavigation:
  key: BlueHats
  order: 25
initiatives:
  - url: /gazette/
    title: La gazette
    description: |
      La gazette BlueHats est une lettre d'information bimestrielle autour des logiciels libres par et pour les administrations publiques.
  - url: /ateliers/
    title: Les ateliers
    description: |
      Les ateliers BlueHats sont des visioconférences publiques consacrées à l'utilisation de logiciels libres par des administrations.
  - url: /rencontres
    title: Les rencontres
    description: |
      Les rencontres BlueHats sont des événements en présentiel où les BlueHats se retrouve pour faire connaissance et collaborer.  Ces rencontres peuvent prendre différentes formes : Sprint Open Source, journées BlueHats lors de salons, etc.
  - url: bluehats-semester-of-code
    title: BlueHats Semester of Code
    description: |
      En partenariat avec CentraleSupélec, la DINUM propose un programme de stages pour développer les contributions de l'administration à des logiciels libres.
---

<div class="fr-grid-row fr-grid-row--gutters">

  {% for initiative in initiatives %}
  <div class="fr-col-12 fr-col-md-6">
    <div class="fr-card fr-enlarge-link">
      <div class="fr-card__body">
        <div class="fr-card__content">
          <h2 class="fr-card__title">
            <a href="{{ initiative.url }}" class="fr-card__link">{{ initiative.title }}</a>
          </h2>
          <p class="fr-card__desc">{{ initiative.description }}</p>
        </div>
      </div>
    </div>
  </div>
  {% endfor %}

</div>

<div class="fr-grid-row fr-grid-row--gutters">
  <div class="fr-col-6">
    <h3><code>BlueHats</code>, c'est qui ?</h3>
    <p>Les <code>BlueHats</code> sont toutes les personnes qui souhaitent montrer qu'elles contribuent à des logiciels libres développés et/ou utilisés par l'administration publique : les agents publics impliqués dans le développement de ces logiciels, bien sûr, mais aussi les citoyens qui reconnaissent que leurs actions pour des logiciels libres aide les projets de l'administration.  N'hésitez pas à <a href="https://man.sr.ht/~codegouvfr/logiciels-libres/espaces-communication-bluehats.md" title="Où échanger avec d'autres agents publics libristes et la communauté BlueHats ? - Lien externe">entrer en contact avec les BlueHats</a>.</p>
    <p><code>BlueHats</code> n'est pas un produit de la DINUM, c'est un mouvement auquel elle contribue en publiant une gazette et en organisant des ateliers - toutes les administrations sont invitées à contribuer à ce mouvement ! Vous souhaitez contribuer aussi ? <a href="mailto:contact@code.gouv.fr">Contactez-nous !</a> 🧢</p>
  </div>
  <div class="fr-col-6 fr-mt-6w">
    <img class="fr-responsive-img" src="/img/bluehats-communaute.jpg"/>
  </div>
</div>
