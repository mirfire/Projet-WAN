---
title: 'Usine de Production'
---

## Description

Site produisant les produits vendus par l'entreprise. Ces produits sont ensuites stockés dans l'[unité de stockage](/sites/unite-de-stockage). Interconnecté au réseau de l'entreprise via le VPN MPLS.

## Matériel Utilisé:

### Routeurs

* [CISCO 2691](/materiel/routeurs#cisco-2691): routeurs de coeur de réseau.

### Switches

! A faire compléter par les équipes gérant le LAN.

### Serveurs

! A faire compléter par les équipes gérant le LAN.

### Postes

! A faire compléter par les équipes gérant le LAN.

## Adressage

[Plan d'adressage](/addressage-ip/listes-des-adresses/usine-de-production).

## Protocole de Routage

* Protocole de routage : **OSPF**  
* Numéro de processus : **1**

|  Router-id  |  Routeur  |
|  :-----          |  :-----          |
|  10.2.0.1 |  UP-C1 |
|  10.2.0.2 |  UP-C2 |
|  10.2.0.3 |  UP-C3 |
|  10.2.0.4 |  UP-CE |

!!! L'interface **f0/1** du routeur "UP-C3" est configuré en **passive-interface** afin que le LAN ne reçoive pas de messages OSPF.

## Contrats

* [Liens](/contrats/liens#usine-de-production).
* [Interconnexions](/contrats/interconnexions#usine-de-production).
