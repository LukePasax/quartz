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
 
name: Lanzichenecco Ufficiale
ac: 18
hp: 58
hit_dice: 9d8 + 18
speed: 7,5m
stats: [18, 16, 14, 10, 10, 12]
saves:
  - Sag: +2
skillsaves:
  - Atletica: +6
  - Intimidire: +3
  - Percezione: +2
  - Persuasione: +3

senses: "Percezione passiva 12"

languages: "Altomanno, Maccheronico"

cr: 4
traits+:
- name: "Ufficiale."
  desc: "Il lanzichenecco ufficiale dispone di vantaggio ai tiri salvezza contro le condizioni di affascinato e spaventato."
  
- name: "Flamberga."
  desc: "Il lanzichenecco ufficiale subisce svantaggio alle prove di caratteristica e ai tiri salvezza basati su Destrezza quando impugna la flamberga in combattimento."
  
actions:
- name: "Multiattacco."
  desc: "Il lanzichenecco doppio soldo effettua due attacchi in mischia."
- name: "Flamberga."
  desc: "Attacco con Arma da Mischia: +6 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 17 (3d8 + 4) danni taglienti."
- name: "Lanzichenetta."
  desc: "Attacco con Arma da Mischia: +6 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 11 (3d4 + 4) danni taglienti."
- name: "Incitamento Imperiale (1/Giorno)."
  desc: "Il lanzichenecco ufficiale incita i suoi subordinati. Fino all’inizio del suo prossimo turno, tutti gli alleati del lanzichenecco ufficiale in grado di udirlo nel raggio di 18 metri da dove si trova dispongono di vantaggio ai tiri per colpire effettuati con un’arma da mischia."
  
reactions:
- name: "Parata."
  desc: "Il lanzichenecco ufficiale aggiunge 3 alla sua CA contro un attacco da mischia che lo colpirebbe. Per farlo, il lanzichenecco ufficiale deve vedere l’attaccante e deve impugnare un’arma da mischia."
```