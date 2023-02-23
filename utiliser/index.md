---
title: Renforcer le recours aux logiciels libres et aux communs numériques
layout: page
eleventyNavigation:
  key: Utiliser
  order: 10
solutions:
- url: https://code.gouv.fr/public/#/sill
  title: Le socle interministériel de logiciels libres (SILL)
  subtitle: Le catalogue de référence des logiciels libres utilisés dans l'administration.
  description: |
    Le SILL est publié depuis 2012 : chaque logiciel présent est utilisé par au moins une administration.  En tant qu'agent public inscrit au SILL, vous pouvez solliciter les référents de chaque logiciel qui pourront répondre à vos questions et vous aider dans l'appropriation de ces solutions.
- url: marches-interministeriels-support-expertise-logiciels-libres
  title: Les marchés interministériels support et expertise à l'usage des logiciels libres
  description: |
    La Direction Générale des Finances Publiques est pilote de deux marchés interministériels à l’usage des logiciels libres. Ces deux marchés ont pour objet de couvrir l’ensemble du cycle de vie d’un logiciel libre au sein du système d'information.
- url: /communs/
  title: Recourir et contribuer à des communs numériques
  description: |
    Le plan d'action encourage le recours à des communs numériques, suivez ce lien pour en apprendre plus.
---

<div class="fr-grid-row fr-grid-row--gutters">

  <div class="fr-highlight">
    <p>Vous souhaitez référencer dans le SILL un logiciel libre utilisé dans votre administration ? <a href="https://sill.code.gouv.fr">Inscrivez-vous !</a></p>
    <p>Vous souhaitez référencer une solution libre dans le catalogue GouvTech ? <a href="https://catalogue.numerique.gouv.fr">C'est ouvert !</a></p>
  </div>

  {% for solution in solutions %}
  <div class="fr-col-12 fr-col-md-6">
    <div class="fr-card fr-enlarge-link">
      <div class="fr-card__body">
        <div class="fr-card__content">
          <h2 class="fr-card__title">
            <a href="{{ solution.url }}" class="fr-card__link">{{ solution.title }}</a>
          </h2>
          <p class="fr-card__desc">{{ solution.description }}</p>
          <div class="fr-card__end">
            <p class="fr-card__detail">{{ solution.subtitle }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  {% endfor %}

</div>
