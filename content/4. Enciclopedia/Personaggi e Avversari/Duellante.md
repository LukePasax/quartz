---
tags: 
- creatura
source: "MA"
aliases: duellanti
statblock: inline
---
Come gli [[Spadaccino|spadaccini]], i duellanti sono combattenti professionisti
e virtuosi della scherma, che prestano la loro opera in genere
come guardie del corpo, maestri di spada e lame mercenarie.
```statblock
layout: Brancalonia
source: "MA"
 
name: Duellante
size: Medio (umano)
type: Umanoide
alignment: qualsiasi allineamento
ac: 14
hp: 33
hit_dice: 6d8 + 6
speed: 9m
stats: [10, 16, 12, 10, 12, 14]
skillsaves:
  - Atletica: +2
  - Intrattenere: +4

senses: "Percezione passiva 11"

languages: "Volgare"

cr: 1

traits:
- name: "Duello."
  desc: "Se il duellante si trova entro un 1,5 m da un avversario e non è presente nessun’altra creatura entro 1,5 m da lui, aggiunge 3 (1d6) ai tiri per i danni."
  
actions:
- name: "Multiattacco."
  desc: "Il duellante effettua tre attacchi in mischia: due con lo stocco e uno con il pugnale."
- name: "Stocco."
  desc: "Attacco con Arma da Mischia: +5 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 7 (1d8 + 3) danni perforanti."
- name: "Pugnale."
  desc: "Attacco con Arma da Mischia o a Distanza: +5 al tiro per colpire, portata 1,5 m o gittata 6/18 m, un bersaglio. Colpito: 5 (1d4 + 3) danni perforanti."

reactions:
- name: "Parata."
  desc: "Il duellante aggiunge 2 alla sua CA contro un attacco in mischia che lo colpirebbe. Per farlo, il duellante deve vedere l’attaccante e deve impugnare un’arma da mischia."
```