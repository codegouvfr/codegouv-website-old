---
title: Recourir et contribuer aux communs numériques
layout: page
eleventyNavigation:
  key: Communs
  order: 30
communsNumeriques:
  - url: https://www.openstreetmap.fr
    title: OpenStreetMap
    description: |
      OpenStreetMap est une carte coopérative librement réutilisable et à laquelle les administrations sont invitées à contribuer.<br><br>Vous pouvez vous rapprocher de l'association OpenStreetMap France pour plus d'information.
  - url: https://fr.openfoodfacts.org
    title: Open Food Facts
    description: |
      Open Food Facts est une base de données sur les produits alimentaires faite par tout le monde, pour tout le monde.  Les administrations sont invitées à y contribuer.<br><br>Vous pouvez vous rapprocher de l'association Open Food Facts pour plus d'information.
  - url: https://www.wikimedia.fr
    title: Les projets Wikimedia
    description: |
      Les projets Wikimedia, notamment Wikipédia, Commons et Wikidata, proposent des ressources librement réutilisables et auxquelles les administrations sont invitées à contribuer.<br><br>Vous pouvez vous rapprocher de l'association Wikimedia France pour plus d'information.
  - url: https://fr.vikidia.org/wiki/Vikidia:Association_Vikidia
    title: Vikidia
    description: |
      Vikidia est une encyclopédie francophone collaborative, libre et gratuite, à destination du jeune public. Y contribuent majoritairement des enfants, des adolescents, ainsi que des enseignants et leurs élèves. L'association Vikidia est soutenue via l'Accélérateur d'initiatives citoyennes.
  - url: https://www.infoclimat.fr
    title: Infoclimat
    description: |
      L’association Infoclimat produit, collecte et met à disposition des données météorologiques et climatiques.  L'association Infoclimat est soutenue via l'Accélérateur d'initiatives citoyennes.
admCommunsNumeriques:
  - url: https://transport.data.gouv.fr
    title: transport.data.gouv.fr
    description: |
      Le Point d’Accès National aux données de transport a pour
      but de rassembler les données de toute l’offre de mobilité à
      travers la France.
    imgSrc: /img/transport.jpg
  - url: https://adresse.data.gouv.fr
    title: adresse.data.gouv.fr
    description: |
      Référencer l’intégralité des adresses du territoire et les
      rendre utilisables par tous : que vous soyez une commune,
      une entreprise ou un simple citoyen, vous pouvez contribuer.
    imgSrc: /img/bal.jpg
  - url: https://datagir.ademe.fr
    title: datagir.ademe.fr
    description: |
      Datagir vous accompagne dans la compréhension et
      l’intégration de données environnementales avec des
      ressources libres d’utilisation, pour que communs numériques
      riment avec accélération de la transition écologique.
    imgSrc: /img/datagir.jpg
  - url: https://acceslibre.beta.gouv.fr
    title: acceslibre.beta.gouv.fr
    description: |
      Acceslibre collecte et met à disposition les informations essentielles à une personne en situation de handicap pour savoir si le lieu ouvert au public dans lequel elle souhaite se rendre lui est accessible.  La base de données est sous licence ouverte 2.0 et chacun peut y contribuer et la réutiliser.
    imgSrc: /img/acceslibre.jpg
---

<div class="fr-highlight">
  <p>Cette page vise à valoriser les démarches de communs numériques engagées par les administrations.  Elle référence aussi des communs numériques libres et collaboratifs auxquels le secteur public contribue déjà.  Les références proposées sur cette page sont appelées à évoluer au fil du temps.</p>
</div>

### Des communs numériques déjà utilisés dans le secteur public

On ne présente plus les projets Wikimédia, OpenStreetMap ou Open Food Facts.  Ces communs numériques libres et collaboratifs font déjà l'objet de contributions de la part de l'administration et nous vous encourageons à y contribuer.

<div class="fr-grid-row fr-grid-row--gutters">

  {% for communNumerique in communsNumeriques %}
  <div class="fr-col-12 fr-col-md-4">
    <div class="fr-card fr-enlarge-link">
      <div class="fr-card__body">
        <div class="fr-card__content">
          <h2 class="fr-card__title">
            <a href="{{ communNumerique.url }}" class="fr-card__link">{{ communNumerique.title }}</a>
          </h2>
          <p class="fr-card__desc">{{ communNumerique.description }}</p>
        </div>
      </div>
    </div>
  </div>
  {% endfor %}

</div>

### Des démarches de mise en commun initiées par l'administration

Ces produits de l'administration publient des ressources sous licence libre et sont ouverts à la collaboration : nous vous invitons à les découvrir et à y contribuer.

<div class="fr-grid-row fr-grid-row--gutters">

  {% for admCommunNumerique in admCommunsNumeriques %}
  <div class="fr-col-12 fr-col-md-3">
    <div class="fr-card fr-enlarge-link">
      <div class="fr-card__body">
        <div class="fr-card__content">
          <h2 class="fr-card__title">
            <a href="{{ admCommunNumerique.url }}" class="fr-card__link">{{ admCommunNumerique.title }}</a>
          </h2>
          <p class="fr-card__desc">{{ admCommunNumerique.description }}</p>
        </div>
      </div>
      <div class="fr-card__header">
        <div class="fr-card__img">
          <img src="{{ admCommunNumerique.imgSrc }}" class="fr-responsive-img" alt="">
        </div>
      </div>
    </div>
  </div>
  {% endfor %}

</div>

<div class="fr-highlight">
  <p>Vous souhaitez proposer d'autres communs numériques d'intérêt général ?  N'hésitez pas à nous <a href="mailto:contact@code.gouv.fr">contacter</a> !</p>
</div>
