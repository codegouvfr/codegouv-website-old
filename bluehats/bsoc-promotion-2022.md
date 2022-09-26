---
title: "BlueHats Semester of Code : la nouvelle promotion"
layout: page
people:
  - projectUrl : https://man.sr.ht/~etalab/logiciels-libres/bsoc2022/sysma.md
    projectName: Sysma
    name: Antoine Simon
    description: |
      Après deux années à CentraleSupélec, j’ai choisi d’effectuer une année de césure pour vivre une première expérience professionnelle. Ayant beaucoup apprécié mes cours d’informatique en école et étant particulièrement motivé par l’idée de contribuer au bien commun dans mon activité professionnelle, j’ai rejoint la première promotion du BlueHats Semester of Code.
      <br><br>
      Dans le cadre du programme, je contribue au logiciel libre Sysma développé par l’Établissement Public Territorial du Bassin de la Sèvre Nantaise et servant au suivi de l'état des cours d'eau et des travaux qui y sont menés.
    imgSrc: /img/bsoc2022/antoine_simon.jpg
  - projectUrl : https://man.sr.ht/~etalab/logiciels-libres/bsoc2022/environmental-sensing.md
    projectName: Environmental Sensing
    name: Dimitri Martin
    description: |
      J’ai intégré CentraleSupélec après un bac Scientifique et une classe préparatoire Physique et Technologie.
      <br><br>
      Avec Philippe Thomy, je travaille sur le logiciel Environmental Sensing qu’il a créé l’année dernière et dont le but est de faciliter l’exploitation des données environnementales.
    imgSrc: /img/bsoc2022/dimitri_martin.jpeg
  - projectUrl : https://man.sr.ht/~etalab/logiciels-libres/bsoc2022/openfoodfacts.md
    projectName: Open Food Facts
    name: Gabriel Ben Zenou
    description: |
      Après ma 2ème année à CentraleSupélec, j’ai décidé de réaliser une année de césure pour enrichir mon expérience tant professionnelle que sociale. Avec pour objectif de m’essayer au développement informatique ainsi que de découvrir des voies professionnelles éthiques et responsables, j’ai rejoint le programme BlueHats Semester of Code.
      <br><br>
      Dans ce cadre, je travaille désormais en tant que stagiaire aux côtés de l’association Open Food Facts pour aider au développement de l’application libre éponyme, chargée de donner accès aux données nutritionnelles et écologiques des produits alimentaires aux populations.
    imgSrc: /img/bsoc2022/gabriel_ben_zenou.png
  - projectUrl : https://man.sr.ht/~etalab/logiciels-libres/bsoc2022/onyxia.md
    projectName: Onyxia
    name: Mohamed Amine Ben Salha
    description: |
      Je suis étudiant à CentraleSupélec et j'espère suivre une carrière dans la science des données. Dans mon cursus, j'ai eu l'opportunité de contribuer à des projets sur le machine learning et le big data qui m'ont permis d'acquérir les compétences nécessaires pour développer des algorithmes de data science. Cependant, il me manquait les compétences nécessaires pour déployer ces algorithmes afin de les exposer au monde. C'est pourquoi j'ai choisi de participer au programme Bluehats où je contribue à un projet open-source, Onyxia.
      <br><br>
      Ce stage me permet d'acquérir de nouvelles compétences en DevOps et en intégration continue tout en mettant en pratique mes compétences en science des données. De plus, les frameworks open source ont toujours été au cœur de mes projets et ce stage me permet de mieux appréhender la politique des projets open source et de leur communauté.
    imgSrc: /img/bsoc2022/mohamed_amine_ben_salha.jpg
  - projectUrl : https://man.sr.ht/~etalab/logiciels-libres/bsoc2022/e-combox.md
    projectName: e-comBox
    name: Sarah Orbach
    description: |
      Je code surtout depuis mon entrée en école d’ingénieur et j'effectue un stage en développement pour mon premier semestre de césure.
      <br><br>
      Dans le cadre du BlueHats Semester of Code, je contribue au projet e-comBox pour l’éducation nationale qui permet à des professeurs de BTS commerce de créer des sites d’études de cas pour leurs étudiants.
    imgSrc: /img/bsoc2022/sarah_orbach.png
  - projectUrl : https://man.sr.ht/~etalab/logiciels-libres/bsoc2022/vlc.md
    projectName: VideoLAN
    name: Yann Lochet
    description: |
      Actuellement en césure de mon cursus ingénieur CentraleSupélec, j'ai rejoint le programme BlueHats Semester of Code afin de contribuer à VLC media player et d'en améliorer le support sur téléphone GNU/Linux.
      <br><br>
      Libriste convaincu, c'est pour moi une excellente occasion de contribuer à un projet open-source mature tout en découvrant le service public.
    imgSrc: /img/bsoc2022/Blank_man_placeholder.svg
---

<div class="fr-grid-row fr-grid-row--gutters">

  {% for person in people %}
  <div class="fr-col-12 fr-col-md-4">
    <div class="fr-card">
      <div class="fr-card__body">
        <div class="fr-card__content">
          <h2 class="fr-card__title">{{ person.name }}</h2>
          <p class="fr-card__desc">{{ person.description }}</p>
        </div>
        <div class="fr-card__footer">
          <a class="fr-link fr-icon-arrow-right-line fr-link--icon-right" href="{{ person.projectUrl }}">
            En savoir plus sur {{ person.projectName }}
          </a>
        </div>
      </div>
      <div class="fr-card__header">
        <div class="fr-card__img">
          <img src="{{ person.imgSrc }}" class="fr-responsive-img fr-ratio-1x1" alt="">
        </div>
      </div>
    </div>
  </div>
  {% endfor %}

</div>
