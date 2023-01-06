---
title: Atelier BlueHats 🧢 - Présentation de inseca (DGAC)
date: 2023-01-06
layout: page
tags: bluehats
---

*Intervention de Vivien Malerba (DGAC)*

Le logiciel [INSECA](https://github.com/DGAC/inseca) permet de créer un ou plusieurs "master" d'OS sécurisé basés sur un live Debian puis de les déployer sur des PC ou serveurs, que ce soit sous forme de clé USB bootables (utilisable sur n'importe quel PC ou presque), ou installé sur le HDD/SSD interne d'un PC ou serveur. Chaque système ainsi déployé contient par ailleurs une partition chiffrée pour le stockage des données. INSECA intègre aussi un outillage pour gérer les configurations des "master" et déployer et assurer un support aux systèmes déjà déployés. Si besoin, une VM Windows (très bridée) peut être intégrée au sein de ces "master".

La sécurité repose sur le fait d'être basé sur un live Debian (impossibilité pour un attaquant d'assurer de la persistance après compromission si compromission), sur des mécanisme de contrôle d'intégrité, la prise en charge des mises à jour ainsi que du sandboxing des applications.

Ce système est utilisé en interne DGAC/DSNA/DTI pour permettre des accès réseaux particuliers en télétravail (les PC Windows n'étant pas assez sécurisés pour cette utilisation) par une soixantaine de personnes.

<iframe title="Atelier BlueHats : présentation de inseca (DGAC)" src="https://tube.numerique.gouv.fr/videos/embed/c4a868fd-53cd-49b0-955c-e168f3ee78f2" allowfullscreen="" sandbox="allow-same-origin allow-scripts allow-popups" width="560" height="315" frameborder="0"></iframe>
