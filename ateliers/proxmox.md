---
title: Atelier BlueHats 🧢 - Présentation de Proxmox
date: 2021-01-22
layout: page
tags: bluehats
---

Intervention de Pierre-Yves Fraisse

- [Télécharger la présentation](https://cloud.telecomste.fr/index.php/s/d56yxfDtFjkHYWz)

Proxmox est une plateforme opensource (AGPL v3) de virtualisation alternative à VMWare, HyperV, Xen ... depuis 2008 qui repose sur Debian. Elle permet la virtualisation de serveurs (machines virtuelles KVM et containers LXC) mais aussi du réseau (VLan, Nat, agrégation de ports, switchs virtuels, ...) et du stockage (LVM, ZFS mais aussi iScsi, Ceph, NFS, CIFS, RBD, ...) la portant ainsi à une solution d'hyperconvergence.

Une interface web permet de gérer facilement la haute disponibilité (en miroir à 2 hosts ou en cluster à partir de 3 hosts), les transferts de machines entre hosts à chaud, et tout le paramétrage.

Etant opensource, Proxmox n'impose pas les contraintes matérielles (notamment sur le stockage ou le réseau) des solutions propriétaires et permet des architectures ouvertes et peu dépendantes du matériel.

Son API lui permet également d'être pilotée facilement par un outil d'orchestration externe et son export des données de performance natif (InfluxDB) permet de créer des tableaux de bord (par exemple avec Grafana) ou de le connecter facilement à un système de supervision.

Un service d'assistance/support payant est disponible si la communauté de suffit pas.

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;"> <iframe style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden" frameborder="0" type="text/html" src="https://www.dailymotion.com/video/x83k79m" width="100%" height="100%" allowfullscreen > </iframe> </div>
