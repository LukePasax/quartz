---
tags: 
- creatura
source: "LI"
statblock: inline
---
```statblock
layout: Brancalonia
monster: Lanzichenecco
source: "LI"

name: Lanzichenecco Doppio Soldo
ac: 17
hp: 45
hit_dice: 6d8 + 18
stats: [16, 14, 16, 10, 12, 12]
saves:
  - For: +5
  - Cos: +5
skillsaves:
  - Atletica: +5
  - Intimidire: +3

cr: 3

traits+:
- name: "Doppio Soldo."
  desc: "Il lanzichenecco doppio soldo dispone di vantaggio ai tiri salvezza contro le condizioni di affascinato e spaventato."
  
- name: "Flamberga."
  desc: "Il lanzichenecco doppio soldo subisce svantaggio alle prove di caratteristica e ai tiri salvezza basati su Destrezza quando impugna la flamberga in combattimento."

actions:
- name: "Multiattacco."
  desc: "Il lanzichenecco doppio soldo effettua due attacchi in mischia."
- name: "Flamberga."
  desc: "Attacco con Arma da Mischia: +5 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 16 (3d8 + 3) danni taglienti."
- name: "Lanzichenetta."
  desc: "Attacco con Arma da Mischia: +4 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 9 (3d4 + 2) danni taglienti."
  
reactions:
- name: "Parata."
  desc: "Il lanzichenecco doppio soldo aggiunge 2 alla sua CA contro un attacco in mischia che lo colpirebbe. Per farlo, il lanzichenecco doppio soldo deve vedere l’attaccante e deve impugnare un’arma da mischia."
```