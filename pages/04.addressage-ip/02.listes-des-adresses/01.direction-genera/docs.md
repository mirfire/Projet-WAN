---
title: 'zDirection générale'
---

```
10.0.0.0/16	Direction générale (DG)		
	10.0.0.0	/30	DG-CE ↔ PE1
	10.0.0.4	/30	DG-CE ↔ DG-C1
	10.0.0.8	/30	DG-C2 ↔ DG-C1
	10.0.0.12	/30	DG-C3 ↔ DG-C1
	10.0.0.16	/30	DG-C3 ↔ DG-C2
	10.0.0.20	/30	DG-C2 ↔ DG-BOX
	10.0.1.0	/24	LAN
```
|  Sous-réseau  |  CIDR  |  Lien  |
|  :-----          |  :-----          |  :-----          |
|  10.0.0.0 |  /30 |  DG-CE ↔ PE1 |
|  10.0.0.4 |  /30 |  DG-CE ↔ DG-C1 |
|  10.0.0.8 |  /30 |  DG-C2 ↔ DG-C1 |
|  10.0.0.12 |  /30 |  DG-C3 ↔ DG-C1 |
|  10.0.0.16 |  /30 |  DG-C3 ↔ DG-C2 |
|  10.0.0.20 |  /30 |  DG-C2 ↔ DG-BOX |
|  10.0.1.0 |  /24 |  LAN |
