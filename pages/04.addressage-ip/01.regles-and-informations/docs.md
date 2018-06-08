---
title: 'Règles & Informations'
---

L'adressage du réseau a été fait en suivant quatre règles :

1. **Les plages d'adresses sont assignées en partant du coeur de réseau.**
    * Les plages IP connectées au coeur de réseau auront les numéros les plus bas.
    * Les LAN utilisateurs auront les plages les plus hautes.
2. **Sur un lien, le routeur avec un numéro le plus petit aura l'adresse la plus petite.**
3. **Sur un lien, le routeur étant le plus à l'intérieur du réseau l'adresse la plus petite.**
4. **Les passerelles *(routeurs)* menant vers les LANs auront toujours la dernière adresse disponible de la plage qu'ils occuppent.**
    * Exemple: un LAN avec une plage `192.168.20.0/24` aura comme passerelle l'IP `192.168.20.254`.

Les règles 2 et 3 ont été mises en place pour permettre de savoir quel interface possède quelle IP sur un lien, si l'on ne connaît que la plage d'adresse de ce lien. C'est assez utile lorsqu'on se base sur un schéma pour répliquer le réseau.