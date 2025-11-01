---
tags: 
- creatura
source: "MA"
aliases: agenti di equitaglia
statblock: inline
---
Sono i Cacciatori di Taglia di rango inferiore. Si occupano delle prime indagini e
dei casi meno pericolosi, per poi raggrupparsi o invocare l’aiuto di un superiore
quando si tratta di arrestare canaglie di un certo peso.

```statblock
layout: Brancalonia
source: "MA"
 
name: Agente di Equitaglia
size: Medio (qualsiasi razza)
type: Umanoide
alignment: qualsiasi allineamento
ac: 13
hp: 16
hit_dice: 3d8 + 3
speed: 9m
stats: [10, 14, 12, 13, 13, 12]
skillsaves:
  - Furtività: +4
  - Percezione: +3
  - Sopravvivenza: +3 

senses: "Percezione passiva 13"

languages: "Maccheronico, Volgare"

cr: 1/2

traits:
- name: "Udito e Vista Acuti."
  desc: "L’agente dispone di vantaggio alle prove di Saggezza (Percezione) basate sull’udito o sulla vista."
  
actions:
- name: "Multiattacco."
  desc: "L’agente di Equitaglia può effettuare due attacchi in mischia: uno con la spada corta e uno con il pugnale."
- name: "Spada Corta."
  desc: "Attacco con Arma da Mischia: +4 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 5 (1d6 + 2) danni perforanti."
- name: "Pugnale."
  desc: "Attacco con Arma da Mischia o a Distanza: +4 al tiro per colpire, portata 1,5 m o gittata 6/18 m, un bersaglio. Colpito: 4 (1d4 + 2) danni perforanti."
- name: "Balestra Pesante."
  desc: "Attacco con Arma a Distanza: +4 al tiro per colpire, gittata 30/120 m, un bersaglio. Colpito: 7 (1d10 + 2) danni perforanti."
- name: "Rete."
  desc: "Attacco con Arma a Distanza: +4 al tiro per colpire, gittata 1,5/4,5m, una creatura di taglia Grande o inferiore. Colpito: Il bersaglio è trattenuto. Una creatura può usare la sua azione per effettuare una prova di Forza con CD 10 per liberare se stessa o un’altra creatura nella rete, terminando l’effetto in caso di successo. Infliggendo 5 danni taglienti alla rete (CA 10), il bersaglio è liberato senza subire danni e la rete è distrutta."
```