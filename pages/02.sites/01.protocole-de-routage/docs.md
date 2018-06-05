---
title: 'Protocoles de routage'
published: false
visible: true
---

#### Direction générale

Protocole de routage : Routage statique

#### Agence commerciale

Protocole de routage : RIPv2

!!! L'interface **f0/1** du routeur "AC-C3" est configuré en **passive-interface**.

#### Usine de production

Protocole de routage : OSPF  
Numéro de processus : 1

|  Router-id  |  Routeur  |
|  :-----          |  :-----          |
|  10.2.0.1 |  UP-C1 |
|  10.2.0.2 |  UP-C2 |
|  10.2.0.3 |  UP-C3 |
|  10.2.0.4 |  UP-CE |

!!! L'interface **f0/1** du routeur "UP-C3" est configuré en **passive-interface**.

#### Unité de stockage

Protocle de routage : EIGRP  
Numéro de processus : 1

!!! L'interface **f0/1** du routeur "US-C3" est configuré en **passive-interface**.