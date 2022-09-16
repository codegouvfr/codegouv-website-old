---
title: Atelier BlueHats 🧢 - Présentation de NixOS et son écosystème
date: 2022-09-16
layout: page
tags: bluehats
---

*Intervention de [Ryan Lahfa](https://ryan.lahfa.xyz/), développeur libriste.

[NixOS](https://nixos.org) est une distribution Linux particulière, derrière cette distribution, il existe un écosystème développé depuis 2003.
Culminant à la thèse de Nix en 2006, le gestionnaire de paquets (de la même nature que \`apt-get\` ou \`rpm\`), central dans l'écosystème.

Nix se distingue des gestionnaires de paquets usuels en l'adoption d'un langage de programmation reposant sur les paradigmes fonctionnels pour décrire les logiciels empaquetés : [nixpkgs](https://github.com/NixOS/nixpkgs/) le « centre logiciel » de l'écosystème Nix en est son représentant canonique.

NixOS se distingue quant à lui en réutilisant intensivement ce langage afin de créer un langage de configuration « natif » au système, appelé le système de module NixOS, il est semblable à un système expert de configuration de services (e.g. serveurs web, serveurs applicatifs, et plus encore).

Cette présentation couvre ces aspects :

-   Présentation des idées de bases de Nix: abandon du modèle FHS, chemin identifié par une empreinte cryptographique, dérivations comme généralisation du concept de paquet
-   Présentation de ce qu'on peut faire avec Nix: scripts universels auto-empaquetés, diminution de la surface d'attaque, production d'images en tout genre (Docker, machines virtuelles)
-   Présentation des idées de bases de NixOS: la dérivation « système », le système de modules NixOS, retours en arrière natifs
-   Présentation de ce qu'on peut faire avec NixOS: capturer son système sous forme d'expression, gérer des flottes de serveurs, tester sans peur, introspecter son système

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;"> <iframe style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden" frameborder="0" type="text/html" src="https://www.dailymotion.com/embed/video/x8dqjm5" width="100%" height="100%" allowfullscreen > </iframe> </div>
